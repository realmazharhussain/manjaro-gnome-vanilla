# manjaro-gnome-vanilla
A Manjaro ISO with Vanilla Gnome experience

## How to download?
- Go to the [latest release](https://github.com/realmazharhussain/manjaro-gnome-vanilla/releases/latest) of this repository
- Download the `.zip` file and its associated `.z01` and `.sha512` files

  For example;

  ```
  manjaro-gnome-vanilla-22.04-220416-linux515.iso.zip
  manjaro-gnome-vanilla-22.04-220416-linux515.iso.z01
  manjaro-gnome-vanilla-22.04-220416-linux515.iso.sha512
  ```

  OR

  ```
  manjaro-gnome-vanilla-22.04-minimal-220416-linux515.iso.zip
  manjaro-gnome-vanilla-22.04-minimal-220416-linux515.iso.z01
  manjaro-gnome-vanilla-22.04-minimal-220416-linux515.iso.sha512
  ```

- Extract (the `.iso` file from) the zip file

  **Note:** In order to open the `.zip` file, its `.z01` file is required to be in the same folder as the `.zip` file.

- Make sure the `.iso` file is in the same folder as the `.sha512` file
- Make sure the `.iso` file is intact by running the command

  ```bash
  sha512sum --check /path/to/sha512_file
  ```

  For example;

  ```bash
  sha512sum --check manjaro-gnome-vanilla-22.04-220416-linux515.iso.sha512
  ```

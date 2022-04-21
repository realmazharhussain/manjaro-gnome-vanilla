# manjaro-gnome-vanilla
A Manjaro ISO with Vanilla Gnome experience

## How to download?
- Go to the [latest release](https://github.com/realmazharhussain/manjaro-gnome-vanilla/releases/latest) of this repository
- Download the `.zip` file and its associated `.z01` and `.sha512` files

  For example;

  `manjaro-gnome-vanilla-22.04-220416-linux515.iso.zip` \
  `manjaro-gnome-vanilla-22.04-220416-linux515.iso.z01` \
  `manjaro-gnome-vanilla-22.04-220416-linux515.iso.sha512`

  OR

  `manjaro-gnome-vanilla-22.04-minimal-220416-linux515.iso.zip` \
  `manjaro-gnome-vanilla-22.04-minimal-220416-linux515.iso.z01` \
  `manjaro-gnome-vanilla-22.04-minimal-220416-linux515.iso.sha512`

- Make sure all three of the downloaded files are in the same folder
- Combine the split files (`.zip` and `.z01`) into a single/complete zip file with the command

  ```bash
  zip --fix /path/to/zip --out /path/to/new_zip_file
  ```

  For example;

  ```bash
  zip --fix manjaro-gnome-vanilla-22.04-220416-linux515.iso.zip --out manjaro-gnome-vanilla-complete.zip
  ```

- Extract the zip file and you'll have a `.iso` file
- Make sure the `.iso` file is in the same folder as the `.sha512` file
- Make sure the resulting `.iso` file is intact by running the command

  ```bash
  sha512sum --check /path/to/sha512_file
  ```

  For example;

  ```bash
  sha512sum --check manjaro-gnome-vanilla-22.04-220416-linux515.iso.sha512
  ```

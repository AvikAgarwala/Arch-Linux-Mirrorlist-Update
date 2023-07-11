# :mirror: MIRROR LIST UPDATE

## This script is used to update the mirrorlist located in `/etc/pacman.d/`.

`Step 1:` Install reflector.
```bash
  sudo pacman -S reflector
```

`Step 2:` Download the [mirror-update.sh](https://github.com/AvikAgarwala/Arch-Linux-Mirrorlist-Update/blob/main/mirror-update.sh) script.

`Step 3:` Grant executable permission to the script file.
```bash
  chmod +x mirror-update.sh
```

`Step 4:` Execute the script.
```bash
  sudo sh mirror-update.sh
```
`Note:` This will create a new file named `mirrorlist.bak` inside `/etc/pacman.d/`.

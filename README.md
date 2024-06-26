Small custom boot animation theme script for plymouth

Needs the plymouth script plugin

Supports password input (dialog) and messages (like on updates)

Setup:
```bash
sudo cp -r custom_animate /usr/share/plymouth/themes/
sudo plymouth-set-default-theme custom_animate -R
```


This repository is mirrored from https://git.huber.cloud/moritz/custom-boot-animation

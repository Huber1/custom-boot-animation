Small custom boot animation theme script for plymouth

Needs the plymouth script plugin

Supports password input (dialog) and messages (like on updates)

> [!CAUTION]
> Use at your own risk. You should know what you are doing

Setup:
```bash
sudo cp -r custom_animate /usr/share/plymouth/themes/
sudo plymouth-set-default-theme custom_animate -R
```

> [!NOTE]
> A new (in-the-works) version based on the bgrt theme (without animation) can be found in the `new` branch



This repository is mirrored from https://git.huber.cloud/moritz/custom-boot-animation


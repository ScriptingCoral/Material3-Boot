# Material3-Boot
A material design 3 theme for rEFInd

### If you haven't already, install rEFInd and git:
```
pacman -S refind git
refind-install
```

### Then execute the following commands:

```
cd /boot/EFI/refind
mkdir themes
cd themes
git clone https://github.com/ScriptingCoral/Material3-Boot.git material3
cd ..
nano refind.conf
```

### Scroll to the bottom of the file and append (in a new line):

```
include themes/material3/theme.conf
```

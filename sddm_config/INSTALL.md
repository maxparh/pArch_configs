# Requirments
---
### Necesarry:

[sddm](https://github.com/sddm/sddm) - basic kde display manager
[sddm-theme-corners](https://github.com/aczw/sddm-theme-corners) - theme corners for sddm

# Installation
---
1. Install both [sddm](https://github.com/sddm/sddm) and [sddm-theme-conf](https://github.com/aczw/sddm-theme-corners)
2. Enable theme corners. On Arch or pArch u need to create a `theme.conf` file in `etc/sddm.conf.d/` and add strings:
```
[Theme]
Current=corners
```
3. run `sudo mv ~/yourDownloadPath/theme.conf /usr/share/sddm/themes/corners/` 

### Note
---
To change your colors, background, or other settings, check [sddm-theme-config-configuration-guide](https://github.com/aczw/sddm-theme-corners/blob/main/CONFIG.md)

Thanks for using pArch linux or pArch linux configs
# Grub theme Skrowell edition
For real emerald block fans

![YASHM](https://exa1488.s-ul.eu/k6POxdWM)

# 🚀 Installation for Ventoy

After installing the archive, you need to unzip it to your USB flash drive.
## 📂 Directory Structure
```bash
.(USB flash driv name)/
├── Your folders/          
├── Ventoy/                 
    ├── theme.txt
    ├── all file from archive...
```
# 🚀 Installation for Grub
## 📂 /etc/default/grub
```bash
#Write the path to the theme

GRUB_THEME="/Example/Ventoy/theme.txt"

#Change the resolution for better display

GRUB_GFXMODE=1920x1080x32,auto
GRUB_GFXPAYLOAD_LINUX=keep
```
## ✨ Update the config file
```bash
sudo update-grub
```

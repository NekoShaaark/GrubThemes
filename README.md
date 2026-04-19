# Grub Themes
Collection of GRUB2 themes!

## Installation
### SilverWolf / SilverWolfLvl999 Theme:
***Note: If you are using the SilverWolfLvl999 theme, replace `SilverWolf` with `SilverWolfLvl999` in each command/instruction.***

1. Download and Unzip the required theme files from the **"Release"** section *(or the /grub/ directory)* of this GitHub Repo.

2. Copy `SilverWolf` into grub themes directory.
```shell
sudo cp -r SilverWolf /usr/share/grub/themes/
```

3. Edit `grub` file.
```shell
sudo nano /etc/default/grub
```

4. Add the theme to the bottom of the text file.
```shell
GRUB_THEME="/usr/share/grub/themes/SilverWolf/theme.txt"
```

5. Update grub config.
```shell
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
or
```shell
sudo update-grub
```

6. Reboot your computer to see your new grub theme.

*Other installation instructions will go here when more are added.*


## Credits
- Star Rail themes are edited from [voidlhf's StarRailGrubThemes](https://github.com/voidlhf/StarRailGrubThemes). Go check them out for cool Star Rail themes!
- *Other theme credits will go here when more are added.*


## Preview
![SilverWolf](/preview/SilverWolf_preview.png)
![SilverWolfLvl999](/preview/SilverWolfLvl999_preview.png)

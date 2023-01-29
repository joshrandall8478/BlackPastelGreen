# BlackPastelGreen Kitty Theme

## Theme inspired by the `BlackMetal` theme by [metalelf0](https://github.com/metalelf0).

![Terminal Full](https://i.imgur.com/AzGwcyB.png)
![Terminal Desktop](https://i.imgur.com/5k5GoM8.png)

## Prerequisites
- kitty
- git

## Installation Guide
### **IMPORTANT:** If this is your first time installing custom kitty themes, make sure to have the `themes` directory in the config folder.
```sh
mkdir ~/.config/kitty/themes
```
### Copy and paste (or move) the theme configuration into your themes folder
```sh
git clone https://github.com/joshrandall8478/BlackPastelGreen
cd BlackPastelGreen
cp BlackPastelGreen.conf ~/.config/kitty/themes/
```
## Apply theme
```sh
kitty +kitten themes
```
Navigate to the `User` panel, and select `Black Pastel Green`. Hold shift and M to replace `current-theme.conf`.
# Step 1
```
sudo pacman -S wofi kitty git waybar ttf-font-awesome otf-font-awesome ttf-jetbrains-mono pavucontrol thunar nwg-look papirus-icon-theme fastfetch powerline-fonts ttf-font-awesome otf-font-awesome ttf-jetbrains-mono code ttf-dejavu blueman brightnessctl

git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si


```

# Step 2

**Add repos**

```
git clone https://github.com/the-liberty/LibertyHyprland.git
```

# Step 3

**Copy config**

```
cd LibertyHyprland
cp -r kitty waybar wofi hypr ~/.config

git clone https://github.com/vinceliuice/Graphite-gtk-theme.git

cd Graphite-gtk-theme
./install.sh
```








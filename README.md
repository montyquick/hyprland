# hyprland

This currently is a manual installation of hyprland on arch. A debian version will be produced.  
Future plans include an install script, some options like:
- file manager
- shell
- terminal
Are usually user preference, defaults in this project are; Thunar, Ranger, Bash and Kitty.

There are some AUR packages required for hyprland / wayland systems, these can be installed with either yay or paru (default)

Default theming will be Rose-Pine

Future theme switching has potential, lets get one right first as configuration management becomes an issue. 

## dependencies

The following are required to support the final configuration:

```bash
qt5-wayland
qt5ct
qt6-wayland
qt6ct
qt5-svg
qt5-quickcontrols2
qt5-graphicaleffects
gtk3
polkit-gnome
pipewire
wireplumber
jq
wl-clipboard
cliphist
python-requests
pacman-contrib
```

## main packages

```bash
base-devel
xdg-desktop-portal-wayland
mako
kitty
waybar
wofi
swappy
grim
slurp
thunar
btop
ranger
bat
firefox
gvfs
file-roller
network-manager-applet
thunar-archive-plugin
unzip
papirus-icon-theme
lxappearance
sddm
```

## AUR packages

```bash
swww
swaylock
swaylock-effects
wlogout
nwg-look-bin
hyprland

```
### things to do
Check packages and move them to the correct place, specifically any AUR packages. 
Git clone as required, sometimes safer than AUR, plus no specific with regard to Linux distro


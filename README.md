# Hyprland dotfiles



![2024-10-31-174444_hyprshot](https://github.com/user-attachments/assets/c91015c6-8893-4776-8150-bb4616dc02cc)



These are my somewhat non-complete dotfiles for my Hyprland install. These are currently pretty much based on [Typecraft-devs](https://github.com/typecraft-dev/dotfiles) dotfiles
plus some modifications I have made.


### Needed apps and dependencies

You will need atleast these apps/packages:

- hyprland
- hyprpaper
- hyprlock
- swaync
- wofi / rofi-wayland
- kitty
- starship
- waybar
- zsh
- nwg-look
- catppuccin-gtk-theme-mocha
- fast-syntax-hilighting
- zsh-syntax-hilighting
- zsh-autosuggestions
- cliphist


I use GNU Stow to link my dotfiles to my .config directory. You can easily link you wanted config by issuing command on terminal:

`stow <packagename>`

where the package name is the top folder name of the config package

# Hyprland dotfiles



![2024-10-31-174444_hyprshot](https://github.com/user-attachments/assets/c91015c6-8893-4776-8150-bb4616dc02cc)



These are my somewhat non-complete dotfiles for my Hyprland install. The base config is based on [Typecraft-devs](https://github.com/typecraft-dev/dotfiles) dotfiles
which I have then modified somewhat.


### Needed apps and dependencies

You will need atleast these apps/packages:

- xdg-desktop-portal-gtk
- xdg-desktop-portal-hyprland
- hyprland
- hyprpaper
- hyprlock
- hypridle
- swaync
- wofi / rofi-wayland
- kitty
- starship
- waybar
- zsh
- nwg-look
- catppuccin-gtk-theme-mocha
- zsh-fast-syntax-highlighting
- zsh-syntax-highlighting
- zsh-autosuggestions
- cliphist
- wlogout
- catppuccin-cursors-mocha
- catppuccin-cursors-macchiato
- brigtnessctl (if you need to change laptop screen brightness)
- oh-my-posh
- oh-my-zsh-git
- ttf-jetbrains-mono-nerd
- ttf-meslo-nerd
- qt5ct
- qt6ct

## Arch
``` paru -Syu xdg-desktop-portal-gtk xdg-desktop-portal-hyprland hyprland hyprpaper hyprlock hypridle swaync wofi rofi-wayland kitty starship waybar zsh nwg-look catppuccin-gtk-theme-mocha zsh-fast-syntax-highlighting zsh-syntax-highlighting cliphist wlogout catppuccin-cursors-mocha brightnessctl oh-my-posh oh-my-zsh-git ttf-jetbrains-mono-nerd ttf-meslo-nerd qt5ct qt6ct```


I use GNU Stow to link my dotfiles to my .config directory. You can easily link your wanted config by issuing command on terminal:

`stow <packagename>`

where the package name is the top folder name of the config package

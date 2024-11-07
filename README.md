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
- Mission Center
- hyprshot

## Arch (gnome base)
``` paru -Syu fastfetch eza python-pip python-gobject python-screeninfo tumbler brightnessctl nm-connection-editor network-manager-applet gtk4 libadwaita fuse2 imagemagick jq xclip zen-browser kitty htop nautilus nautilus-open-any-terminal python-pywal pinta blueman grim slurp cliphist nwg-look qt6ct waybar rofi-wayland polkit-gnome zsh zsh-completions fzf pavucontrol papirus-icon-theme breeze gvfs wlogout hyprshade waypaper grimblast-git otf-font-awesome ttf-fira-sans ttf-fira-code ttf-firacode-nerd hyprland hyprpaper hyprlock hypridle noto-fonts xdg-desktop-portal-hyprland libnotify kitty qt5-wayland qt6-wayland networkmanager git xdg-desktop-portal-gtk swaync starship catppuccin-gtk-theme-mocha zsh-fast-syntax-highlighting zsh-syntax-highlighting catppuccin-cursors-mocha oh-my-posh-bin oh-my-zsh-git ttf-jetbrains-mono-nerd ttf-meslo-nerd qt5ct qt6ct-kde mission-center hyprshot```



I use GNU Stow to link my dotfiles to my .config directory. You can easily link your wanted config by issuing command on terminal:

`stow <packagename>`

where the package name is the top folder name of the config package

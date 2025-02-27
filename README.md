# dotfiles-waybar
This repository contains all my custom configurations for [**Waybar**](https://github.com/Alexays/Waybar).

### Dependencies
- [**pavucontrol**](https://freedesktop.org/software/pulseaudio/pavucontrol/) - Used in pulseaudio's module.<br>
- [**ddcutil**](http://www.ddcutil.com/) - Control brightness on external monitors.<br>
- [**hyprshot**](https://github.com/Gustash/hyprshot) - Take screenshots

### Theme
- [**Catppuccin/Waybar**](https://github.com/catppuccin/waybar) - Color scheme.

### Font
- [**ttf-font-awesome**](https://fontawesome.com/) - Used by the icons.<br>
- [**Fantasque Sans Mono**](https://github.com/belluzj/fantasque-sans) - Font Family.

### Installation
Follow their [**guide**](https://github.com/Alexays/Waybar) on how to install [**Waybar**](https://github.com/Alexays/Waybar).<br>
Then, just move the files on this repository to `~/.config/waybar/`<br>

### Usage
Make sure that [**Waybar**](https://github.com/Alexays/Waybar) is being executed alongside [**Hyprland**](https://hyprland.org/).<br>
You can do this by adding `exec-once = waybar` to the `hyprland.conf` file. (stored at `~/.config/hypr/`)

### Screenshots
![Example](assets/example.png)

### TO-DO
- [ ] Add a menu to custom-clipboard using rofi and cliphist.
- [ ] Add a menu to custom-notification using swaynotificationcenter.
- [ ] Add a menu to custom-power using rofi (shutdown, restart and logout).
- [ ] Remove background from tray icons, make spacing lesser. (it looks better)
- [ ] Use rofi to add a menu to bluetooth module.
- [ ] Use rofi to add a menu to pulseaudio module.

### Notes
#### Setting up ddcutil for brightness control.
Install [**ddcutil**](http://www.ddcutil.com/).<br>
Load `i2c-dev` on boot if `/dev/i2c-*` devices do no exist.<br>
> You can do this by adding i2c_dev to /etc/modules-load.d/i2c-dev.conf

#### Missing icons
Install [**ttf-font-awesome**](https://fontawesome.com/) and [**Fantasque Sans Mono**](https://github.com/belluzj/fantasque-sans)<br>

#### Adjusting CPU temperature
You can check how to do this [**here**](https://github.com/Alexays/Waybar/wiki/Module:-Temperature).

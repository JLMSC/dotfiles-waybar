# dotfiles-waybar
This repository contains all my custom configurations for [**Waybar**](https://github.com/Alexays/Waybar).

### Dependencies
- [**pavucontrol**](https://freedesktop.org/software/pulseaudio/pavucontrol/) - Used in pulseaudio's module.<br>
- [**ddcutil**](http://www.ddcutil.com/) - Control brightness on external monitors.

### Theme
- [**Catppuccin/Waybar**](https://github.com/catppuccin/waybar)

### Font
- [**ttf-font-awesome**](https://fontawesome.com/)<br>
- [**Fantasque Sans Mono**](https://github.com/belluzj/fantasque-sans)

### Installation
Follow their [**guide**](https://github.com/Alexays/Waybar) on how to install [**Waybar**](https://github.com/Alexays/Waybar).<br>
Then, just move the files on this repository to `~/.config/waybar/`<br>

### Usage
Make sure that [**Waybar**](https://github.com/Alexays/Waybar) is being executed alongside [**Hyprland**](https://hyprland.org/).<br>
You can do this by adding `exec-once = waybar` to the `hyprland.conf` file. (stored at `~/.config/hypr/`)

### Screenshots
![Example](assets/example.png)

### TO-DO
- [ ] Adjust the clock module's hover effect to match the Catppuccin color scheme.
- [ ] Replace the text labels in the left module with matching icons.
- [ ] Display the average temperature (°C) right after the CPU and GPU modules.
- [ ] Expand the power module's functionality; currently, it only executes `shutdown`.
- [ ] Check if adding a notification daemon icon in the center module (after the clock module) is possible.
- [ ] Check if adding a clipboard history icon in the right module (after the PulseAudio module) is possible.
- [ ] Check if adding an OSD icon for Caps Lock and Num Lock in the right module (before the Bluetooth module) is possible.

### Notes
#### Setting up ddcutil for brightness control.
Install [**ddcutil**](http://www.ddcutil.com/).<br>
Load `i2c-dev` on boot if `/dev/i2c-*` devices do no exist.<br>
> You can do this by adding i2c_dev to /etc/modules-load.d/i2c-dev.conf

#### Missing icons
Install [**ttf-font-awesome**](https://fontawesome.com/) and [**Fantasque Sans Mono**](https://github.com/belluzj/fantasque-sans)<br>

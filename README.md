# Personal Dotfiles
Here is a collection of my dotfiles that tries to integrate the Nord-theme as much as possible. At the moment only the [Waybar](https://github.com/Alexays/Waybar) configuration is publicly released, hopefully the rest will follow as well.

### Screenshots

**Waybar**

![Screenshot of waybar](/screenshot.png?raw=true)

## Waybar config
>Highly customizable Wayland bar for Sway and Wlroots based compositors.
Available in Arch community or AUR, openSUSE, and Alpine Linux

I've configured waybar with the Nord-theme in mind as well as trying to take vital information and make it as easy as possible to take in. There is also a script for the custom-module part which simply shows the current cpugovernor (only supports Performance or Schedutil at the moment).
Screenshot follows after list of items in the bar left to right.

### Left
* Clock and date, with **gnome-calendar** open on left-click 
* Input language indicator
* Scratchpad widget, **cycles** contents or **sends** to scratch
* Pacman available updates indicator
* Idle-inhibitor
### Middle
* Workspaces, minimalistic. Configure icons in config
#### Right
* CPU Governor indicator, script in **custom_modules** can be extended
* CPU max frequency and usage in percent
* CPU temperature with warning. Opens **htop** in term on click
* Pulseaudio control. Scroll for volume increase/decrease, click for **pavucontrol** or right-click to quickly **mute** microphone.
* Bluetooth indicator, opens **blueberry** on click
* Network indicator with mouse-over info (Strength, IP, Frequency, Speed etc)
* Tray to keep icons



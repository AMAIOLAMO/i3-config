# i3 CX config

A funny little simple config I did.

It uses `JetBrainsMono Nerd Font Regular font`

Requires the following to be installed:
```
copyq // X11 clipboard manager

bumblebee-status // used for the display of i3 status bar
rofi // used for better display
brightnessctl // for changing display brightness
nitrogen // wallpaper manager
picom // for transparency and window fading animation
```

Do note that this is just a very simple and basic setup, slightly modified the example config given by i3wm

The default window managing will be **tabbed**

## Keybindings
This configuration has changed some default keybindings to match more closely to vim keybindings

the main special key is still your regular Win key (or whatever key you have that matches to `Mod4` in i3)
here on out I will be using `mod` as a replacement for the special key

`mod+q` kill the current focused window

`mod+h` focus left
`mod+j` focus down
`mod+k` focus up
`mod+l` focus right

`mod+Alt+space` toggle floating for the current window

`mod+z` toggles the 1st (main) workspace
`mod+x` toggles the 2nd (dev) workspace
`mod+c` toggles the 3rd (term) workspace
`mod+v` toggles the 4th (chat) workspace

`mod+backspace` go into system mode, in which you can use (l) logout, CTRL+r to reboot, and CTRL+s to shutdown.
While in system mode, you can either use return key, or ESC key to exit out

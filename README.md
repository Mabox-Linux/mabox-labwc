## Mabox config files for Labwc

Mabox provides two Labwc sessions/profiles

- labwc
- mabox-labwc (to be experimental)

Both are very basic at the moment.

### ISO Image
Pre-release ISO is available at [repo.maboxlinux.org/iso/pre-release](https://repo.maboxlinux.org/iso/pre-release/)

### Keybindings
#### Actions

| combination              | action
| ------------------------ | ------
| `A`-`Tab`                | activate next window
| `A`-`F4`                 | close window
| `W`-`a`                  | toggle maximize
| `F11`                    | toggle fullscreen
| `W`-`b`                  | toggle decorations
| `A`-`mouse-left`         | move window
| `A`-`mouse-right`        | resize window
| `A`-`arrow`              | move window to edge
| `W`-`arrow`              | resize window to fill half the output
| `W`-`keypad_1..9`        | resize window to regions
| `A`-`space`              | show the window menu
| `XF86_AudioLowerVolume`  | amixer sset Master 5%-
| `XF86_AudioRaiseVolume`  | amixer sset Master 5%+
| `XF86_AudioMute`         | amixer sset Master toggle
| `XF86_MonBrightnessUp`   | brightnessctl set +10%
| `XF86_MonBrightnessDown` | brightnessctl set 10%-

#### Applications/Launchers

| combination              | application
| ------------------------ | ------
| `A`-`F2`                 | launcher (gmrun)
| `A`-`F3`                 | launcher (bemenu)
| `W`-`Return`, `W`-`t`    | foot
| `W`-`f`                  | filemanager (pcmanfm)
| `W`-`w`                  | webbrowser (firefox)
| `W`-`e`                  | editor (geany)
| `W`-`v`                  | volume (pavucontrol)
| `W`-`r`                  | internet radio (pyradio)
| `W`-`m`                  | sound and music menu (jgmenu)


![](/img/Mabox_Labwc_241231.avif)

[up](./README.md)

# Tobecci's XFCE Libinput config

open `~/.config/libinput-gestures.conf` and put the code below inside the file and save

```conf
#######################
# XFCE
#######################

# three fingers

gesture swipe down 3 xfce4-popup-whiskermenu
gesture swipe left 3 xdotool key shift+alt+Tab
gesture swipe right 3 xdotool key alt+Tab
gesture swipe up 3 xfdesktop --windowlist

# four fingers

gesture swipe up 4 xdotool key alt+F4
gesture swipe down 4 xdotool key ctrl+alt+d
```
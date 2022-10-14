[up](../README.md)


# libinput config for easy navigation
put the code below in `~/.config/libinput-gestures.conf`

```conf
# three finger
# switch to previous desktop
gesture swipe left 3 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "Switch to Previous Desktop"
# switch to next desktop
gesture swipe right 3 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "Switch to Next Desktop"
# show desktop grid
gesture swipe down 3 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "ShowDesktopGrid"
#present windows (all desktops)
gesture swipe up 3 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut ExposeAll

# four fingers
#maximize window
gesture swipe up 4 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "Window Maximize"
# close window
gesture swipe left 4 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "Window Close"
# show activity menu
gesture swipe right qdbus org.kde.kglobalaccel /component/plasmashell org.kde.kglobalaccel.Component.invokeShortcut "manage activities"
# minimize windows
gesture swipe down 4 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "Window Minimize"


# use `qdbus org.kde.kglobalaccel /component/kwin shortcutNames` to show shortcut names
# then use `qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut [shortcut name]` to invoke the shortcut

```

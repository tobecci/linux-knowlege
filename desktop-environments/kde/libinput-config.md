# libinput config for easy navigation
put the code below in `~/.config/libinput-gestures.conf`

```txt
# three finger
gesture swipe left 3 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "Switch to Previous Desktop"
gesture swipe right 3 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "Switch to Next Desktop"
gesture swipe down 3 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "ShowDesktopGrid"
gesture swipe up 3 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut Expose

# four fingers
gesture swipe up 4 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut ExposeAll
gesture swipe left 4 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "Window Close"
gesture swipe right qdbus org.kde.kglobalaccel /component/plasmashell org.kde.kglobalaccel.Component.invokeShortcut "manage activities"
gesture swipe down 4 qdbus org.kde.kglobalaccel /component/kwin org.kde.kglobalaccel.Component.invokeShortcut "MinimizeAll"
```
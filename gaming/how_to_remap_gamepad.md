[up](./README.md)

# How to remap gamepad buttons in lutris

## step 1
install the package [gamepad tool](https://aur.archlinux.org/packages/gamepad-tool-bin)

## step 2
launch the program with `gamepad-tool` (terminal only)

you get whhat is seen below

![gamepad-tool image](./../assets/images/Screenshot_2022-08-14_17-27-57.png)

## step 3
click `create new mapping` the remap the buttons

## step 4
click `copy mapping string` (copies the mapping string to your clipboard)

## step 5
open lutris

- right-click on the game
- click `configure`
- navigate to `system options` tab
- paste the copied string in the `SDL2 gamepad mapping` field (looks like below)  
![sdl2 image](../assets/images/Screenshot_2022-08-14_18-07-36.png)
- start the game
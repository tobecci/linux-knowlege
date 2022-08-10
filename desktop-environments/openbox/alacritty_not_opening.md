[up](./README.md)

# Alacritty not opening

creating a ~/.drirc with the vblank_mode set to 1 has resolved it. Thanks!

`touch ~/.drirc`

```xml
<driconf>
   <device>
       <application name="Default">
           <option name="vblank_mode" value="1" />
       </application>
   </device>
</driconf>

```
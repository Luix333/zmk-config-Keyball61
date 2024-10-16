This keeb created by a group of people who loves keyball.

Special Thanks to: <br>
PCB: *[yangxing844](https://github.com/yangxing844)* <br>
Case: *[delock](https://github.com/delock)* <br>
Firmware: *[Amos698](https://github.com/Amos698)* <br>

# XCMKB session
Thanks for the above contribution and *[inorichi](https://github.com/inorichi/zmk-pmw3610-driver)* too.

## Quick Link
[Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) <br>
[Github, Keymap Editor Setup and Flashing](https://github.com/superxc3/zmk_config_sofle#steps) - using Sofle wireless as reference<br>

## Notes
### Flashing
1. If you only change the keymap, you can just flash to the master side. For Keyball series, master is on the right. That means you dont need to flash left and right.
2. If double press reset button doesnt call out the new folder to drag your uf2, that means you have to double press even faster.
3. You dont need to delete any files in nicenano folder, just drag your new right uf2 to it and ignore and skip any error.
4. Normally doesnt need to repair after format. It will paired automatically.
   
### Charging
5. You can just plug in cable and flip the power button on to charge.
6. You can charge both sides togehter. Slave (left) normally lasts longer than the master (right).
7. If you want to make sure flawless connection, you can plug in cable to right and use as wired mode. Left doesnt need to plug in wire and remains wireless.
8. If you want to keep your battery healthy yet want to make sure flawless connection, you can flip the power button off and plug in cable to right. This makes sure the board is using in wired mode but doesnt always charge the battery.

 
## Trackball Layer
1. `Auto Mouse`: Layer 4 (when you move the trackball, it automatically goes to Layer 4. `J` for left click, `L` for right click, `:"` for middle click, you always can remap to something else in keymap editor. There is timeout for this automouse layer. It is fixed atm).
2. `Scroll`: Layer 5
3. `Snipe`: Layer 6 (cursor moves super slow for precision)

## Trackball Configuration
1. To change the Scroll Layer, go to `zmk-config-Keyball61/config/boards/shields/keyball61/keyball61_right.overlay`: [scroll-layers=5](https://github.com/superxc3/zmk-config-Keyball61/blob/e7d3e26597f22324cf7e9b96c2aa8b27465a058a/config/boards/shields/keyball61/keyball61_right.overlay#L65). Change the number 5 to your preferred layer.
2. To change the defaul CPI, go to `zmk-config-Keyball61/config/boards/shields/keyball61/keyball61_right.conf`: [CONFIG_PMW3610_CPI=1200](https://github.com/superxc3/zmk-config-Keyball61/blob/e7d3e26597f22324cf7e9b96c2aa8b27465a058a/config/boards/shields/keyball61/keyball61_right.conf#L7C1-L7C24). Other trackball config could be changed in the same file too, eg., snipe CPI, scroll direction etc. 

## Suggested Combo
We have added a few combos to the default keymap. Feel free to adjust for your needs. 
![image](https://github.com/user-attachments/assets/1d802a7e-c73a-413e-94e3-8dbdb62e1878)




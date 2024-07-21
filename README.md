# Sofle v1 Modular Case

![](img/01.png)

This case is designed to be used wirelessly. If you need the cutout for TRRS connector, there's a small dent near its position on the case wall. Simply edit the file to make the dent go all the way through the other side to create a hole.

For the case, it is designed to hold a **503450 3.7v Li-Po** battery (~1000mAh). There's no mechanism to hold it in place, so you need to tape it down to the case. The case has 2 cutout on the top edge for placing a [19.6x5.5 power switch](img/power_switch_footprint.jpg) and a 6x6x6 reset button.

The joystick module case is designed to hold a **[KY-023](https://arduinomodules.info/ky-023-joystick-dual-axis-module/)** PCB and a **Xiao ESP32S3** board (other Xiao ESP32 should also fit since they have similar footprint). The board can be powered and connect directly via the USB port, or with a 3.7v battery for wireless connection (you can refer to this [image](img/08.png) for rough estimation of the size of the battery; the height of the battery should be less than 6mm). There's also a cutout for a 6x6x8 latching push button as a power switch for the Xiao if it is to be used with a battery.

The clearance between the rail lips (case) and connector (module) is 0.2mm. If you find that they do not fit properly, you can adjust the size of the rail connector on the module by making a copy of my Onshape project [here](https://cad.onshape.com/documents/8e4b67d99ebe6a9953b51236/w/fc37eb56f099d0099efda1f7) and edit it. The sketch is placed at `Joystick Module/Rail/Rail`.

List of screws and spacers needed for each side:

-   Case:
    -   5x M2x6mm spacer
    -   7x M2x4mm threaded insert
    -   5x M2x8mm screws
-   Joystick module:
    -   4x M2x4mm threaded insert
    -   4x M3x4mm screws
-   Other parts:
    -   5x M2x6mm screws for the top plate

![](img/02.png)

![](img/03.png)

![](img/04.png)

![](img/05.png)

![](img/10.png)

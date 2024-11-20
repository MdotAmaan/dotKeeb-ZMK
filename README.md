# dotKeeb

<<<<<<< Updated upstream
=======
A wireless ergonomic keyboard inspired by the dactyl using low profile switches and a trackball.

[Docs are WIP]

>>>>>>> Stashed changes
![Render](assets/dotKeeb.png)
>  ## Table of contents
>  - [Overview](#overview)
>  - [Part List](#parts)
>  - [Bulid Guide](#build)


## Overview <a name="overview"></a>

This keyboard shares most of the same benefits as other split, concave keyboards while being relatively compact. It also features more aggressive stagger and elevation on the pinky cluster than most other column-staggered keyboards to accommodate for my proportionally shorter pinky fingers. The trackball was positioned next to the home row rather than the thumb region to prevent the thumb from being overused. 

**TODO:** 
- Consider reducing the number of keys by 2
- Add links to parts
- Add diagrams for build
- Finish documenting build process

## Part list <a name="parts"></a>

Quantities listed are for building 2 halves.


| Quantity | Part | Notes |
| -------- | ---- | -------------------------------------------------------------------------------- |
| 52 | **Choc V1 Switch** | *TODO: find ways to reduce this down to 50* |
| 52 | **Choc V1 Hotswap Socket** | Optional, but highly recommended. Lets you pull the electronics out of the case without any desoldering |
| 52 | **Choc V1 Compatible Keycap** | I used MBK keycaps for my build. Other choc V1 keycaps should also work |
| 52 | **THT Diode** | |
| 2 | **nice!nano V2** | |
| 1 | **nice!view Display** | Optional. Used for battery and connection status |
| 2 | **>150mAh 3.7V LiPo Battery** | |
| 1 | **34mm Trackball** | |
| 3 | **Trackball Bearings** | Ceramic (Highly recommended), Roller, and BTUs are supported |
| 1 | **PMW3610 Sensor** | |
| 1 | **PMW3610 Breakout** | [This](https://github.com/victorlucachi/charybdis-pmw3610-breakout/tree/nicenano) is the one I used. You'll need to get it manufactured and assembled at a place like JLCPCB. You might also be able to buy the sensor pre-soldered onto a breakout board|
| 2 | **Power Switch** |  |
| 10 | **5mm x 3mm Magnets** | |
| 12 | **Small Rubber Feet** | [These](https://www.aliexpress.us/item/3256802432366448.html) are the ones I used. There are circular cutouts for them on the base plate.|
| - | **Wire** | Using solid copper wire for the columns works well especially if hotswap sockets are used. For other connections, I used jumper wires. |

### Prints

| Quantity | Part | Notes |
| -------- | ---- | -------------------------------------------------------------------------------- |
| 1 | **dotKeeb_left.stl** |  |
| 1 | **dotKeeb_right.stl** |  |
| 1 | **Charybdis top trackabll adapter** | Both closed and open variants work |
| 1 | **Charybdis bottom trackball adapter** | |
| 1 | **PMW3610 Adapter** | TODO: modify the bottom adapter so this isn't necessary |
| 3 | **Trackball bearing inserts** | Make sure you choose the right one for your bearing type |



## Build Guide [Work in Progress] <a name="build"></a>
#### I would highly recommend watching Joe Scotto's video on [creating better hand-wired keyboards](https://www.youtube.com/watch?v=m7Q5ZjqN-ao) prior to assembly.

Follow the wiring diagram below. Note that the physical columns do not always match the columns of the circuit.
![GuideLeft](assets/guideleft.png)
![GuideRight](assets/guideright.png)
##### *nice!nano V2 and nice!view graphics were taken from https://nicekeyboards.com*

If your batteries are larger than 500mAh, bridge the pads under the board. **Don't bridge them if your batteries are less than 500mAh**

![nicenanopads](assets/nicenanopads.png)

- mention diode direction and legs
- make diagram for other side
	- include displays

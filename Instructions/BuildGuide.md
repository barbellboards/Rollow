# Rollow Build Guide

Rollow is one of the first split keyboards with dedicated thumb encoders...
It's inspired by the ergonomics of a Ferris and the elegance of a Corne.
While also being influenced by my passion for the automotive customization scene.

## Parts

It's recommend that before beginning to build Rollow all the necessary parts should be accounted for.
This insures there aren't any missing pieces in your kit,
if so please contact Barry (EdgelessCorner#1430 or barbellboards@gmail.com)

| Name | 3x6 | 3x5 | Mini | Excluded From Half Kit |
|:-|:-|:-|:-|:-|
| PCB | 2 | 2 | 2 |  |
| Top plate | 2 | 2 | 0 | x |
| Bottom plate | 2 | 2 | 0 | x |
| Gasket Layer | 2 | 2 | 0 | x |
| EVA Foam | 0 | 0 | 2 | - |
| OLED Covers | 2 | 2 | 2 | x |
| OLEDs | 2 | 2 | 2 | x |
| Encoders | 2 | 2 | 2 |  |
| TRRS Jack | 2 | 2 | 2 |  |
| Reset Switch | 2 | 2 | 2 |  |
| Power Switch | 2 | 2 | 2 |  |
| Screws | 18(+2) | 18(+2) | 8(+2) | x |
| OLED Cover Standoffs | 4 | 4 | 4 | x |
| SMD Plate Standoffs | 10 | 10 | 0 | x |
| Kailh Hot Sockets | 40 | 34 | 0 | |
| SMD Diodes | 42(+2) | 36(+2) | 42(+2) | |
| Rubber Pads | 14(+2) | 14(+2) | 0 | x |

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/1.jpg?raw=true)
![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/2.jpg?raw=true)

<sub>*Note: The SMD diodes in this guide are different from the ones in the Kit.*</sub>

## Building

### Step 1: Deciding on sides

What seems like a trivial step, is fairly important.
There have been countless mistakes where people have accidentally solder components on the same side for both halves. Having to desolder SMD parts you just soldered isn't fun.

If it makes life easier you can always put a piece of tape depicting what side your Rollows half represents.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/3.jpg?raw=true)

### Step 2: Microcontrollers and OLED

This example utilizes mill-max sockets to socket the microcontrollers and OLEDs.
It's worth noting that the steps taken are almost identical for non-socketed components.

Start by using some sort of paper based tape, like painters tape, to tape down your sockets.
The tape serves two purposes:

1. The tape helps to keep the sockets from moving when soldering them from the backside of the board.
2. It also stops excess solder from passing the through hole on the microcontrollers and binding it to the sockets.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/5.jpg?raw=true)

Flip the board around and start by soldering opposite ends of each sockets. Soldering both ends is a simple
way to guarantee the sockets wont move.

Once the ends are soldered you can finish off soldering each individual pin of the sockets.

<sub>*Note: Make sure to double check that each of the pins are soldered correctly.
It's not uncommon to miss a pin and only to realize it afterwards when a full column or
row of your keyboard isn't working.*</sub>

With the sockets soldered you can begin adding pins to the sockets.
When adding the pins it usually takes a little force to seat them properly the first time.

<!---Video 9-->
https://user-images.githubusercontent.com/104576748/175922826-d35a4ee9-c350-4928-8001-ba0b7355e799.mp4

[Video Link](https://youtu.be/1avikLniorU)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/10.jpg?raw=true)

Next, you'll need to position the microcontroller on top of the sockets. Make sure the microcontroller
is correctly oriented. You can easily check by looking to see if the microcontrollers
pinout names match those on the pcb.

<sub>*Note: Don't forget to account for the space needed for a lipo battery under the microcontroller
if you're using a bluetooth setup and you desire the battery positioned in this manner.*</sub>

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/11.jpg?raw=true)

Continue with soldering the microcontrollers to the board.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/12.jpg?raw=true)

Finish by snipping off any excess on the pins.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/13.jpg?raw=true)

Remove the microcontroller and double check that all the solder joints look correct.
You can also remove the tape at this point.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/14.jpg?raw=true)

With the microcontroller off you'll have access to the OLED jumpers.
Make sure to bridge these jumpers so the OLED is wired to the correct side of the board.

<!---Video 15a-->
https://user-images.githubusercontent.com/104576748/175925441-be7fb134-d95e-4764-baeb-1b012c1e5dbd.mp4

[Video Link](https://youtu.be/XsF2idFTQ3s)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/15.jpg?raw=true)

If you haven't already soldered the OLED sockets,
you can follow the steps above for socketing the microcontrollers.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/16.jpg?raw=true)

### Step 3: Reset Button, Power Switch, and TRRS Jack

To begin with the reset button, the first thing you'll want to do is pre-solder the through holes.
This will allow for an easier installation of the reset switch shown in the video below.

<!---Video 17-->

https://user-images.githubusercontent.com/104576748/175926210-4ff062fe-000b-45e3-847f-a5232104fa0f.mp4

[Video Link](https://youtu.be/hT-aMZvHc8E)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/18.jpg?raw=true)

With the reset button finished, the next component is the TRRS jack.
Place the TRRS jack in the designated area marked on the board.
Then you'll need to flip the board over and solder the pins.
Using some tape to hold the TRRS jack down can help keep it flush to the pcb.

<!---Video 19-->
https://user-images.githubusercontent.com/104576748/175926894-2209974e-d4e8-4b16-89ff-e38e1ea2901b.mp4

[Video Link](https://youtu.be/7d_xhCn4GK4)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/20.jpg?raw=true)

Lastly with the board still flipped with it's bottom up, solder the power switch.
Similar to the reset button it's easier to pre-solder one of the switches pads and place the
switch on top of it.

<!---Video 21-->
https://user-images.githubusercontent.com/104576748/175927322-5cd1cffa-62c2-4f2e-af08-d5f64f3f1a00.mp4

[Video Link](https://youtu.be/-FwDCMfAFm0)

### Step 4: Diodes

Instead of soldering each individual diode at a time, it's easier to do them in a batch like process.
*Make sure you're soldering the diodes on the front of the board, not the bottom like usual!*
The diodes go where the LED lights would sit within the switches.

Start by adding solder to one side of each pad.

<!---Video 24a-->
https://user-images.githubusercontent.com/104576748/175928332-bc3c9ff2-3cd8-4337-8c2c-73363c156f71.mp4

[Video Link](https://youtu.be/z5ze24Iwil8)


![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/24.jpg?raw=true)

Holding one end of the diode using a pair of tweezers, slide the diode into the solder
while heating the solder with the iron.

<!---Video 24b-->
https://user-images.githubusercontent.com/104576748/175931329-fa7da6e3-7e88-4b27-a1cb-aeaa68791395.mp4

[Video Link](https://youtu.be/Dayoz5wi4J0)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/26.jpg?raw=true)

Finish up by soldering the other ends of the diodes to the board.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/28.jpg?raw=true)

### Step 5: Switch sockets

The switch sockets use an identical process to the diodes except that they
are placed on the bottom side of the pcb.

Start by pre-soldering one side of each socket's pads.

<!---Video 29-->
https://user-images.githubusercontent.com/104576748/175933036-b3dde7f3-a230-4c2d-8cc7-962487a8aaf5.mp4

[Video Link ](https://youtu.be/a_M5lLFL-kc)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/29a.jpg?raw=true)

Place the socket on top of the with the squared off end facing downward

<sub>*Note: Even though the pcb might show the rounded end facing downward it's best for the
square end to face downward. If you already soldered it with the round end downward don't worry
about it. There isn't going to be a huge difference in the end. Just makes putting the bottom plate
on easier.*</sub>

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/30a.jpg?raw=true)

Holding one end of the socket with a pair of tweezers, place the soldering iron within the sockets
"solder valley" holding it until the solder passes through the valley.

<sub>*Note: Be careful not to hold the soldering iron on the board for too long*</sub>

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/31.jpg?raw=true)

Lastly, solder the other end of the socket's valley.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/32.jpg?raw=true)

### Step 6: Encoders

The encoders can be a little tricky to work with. There isn't a lot of room,
so it's recommended to take your time.

<sub>*Note: Be careful with bending the four pins that are aligned to eachother. They're
fairly fragile and can snap off quite easily.*</sub>

Start by bending the farthest outside pin of the encoder just slightly. This step makes
seating the encoder slightly easier.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/22b.jpg?raw=true)

With the pin slightly bent, you can seat the encoder into the board. Start by sliding the legs through the
cylindrical hole in the board. Once the feet are in far enough that they past the bottom edge of the board
or are flush, you can gently push the encoder toward you slotting it in place. This might take a little force.

Afterwards, you can finish with soldering the pins and bridging the jumpers underneath

<!---Video 22-->
https://user-images.githubusercontent.com/104576748/175933178-7931f157-08ca-4c1e-9226-a07fb1c0177f.mp4

[Video Link](https://youtu.be/nH7LEHtE2h0)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/22c.jpg?raw=true)

### Step 7: SMD Plate Standoffs

Start by pre-soldering the standoffs pads. Try to to evenly solder around the plate.
It doesn't have to be perfect. Be careful to not leave the iron on the pads for too long.

<!---Video 34a-->
https://user-images.githubusercontent.com/104576748/175934636-4b9564c5-062e-49ee-9794-8faaa5304cf5.mp4


[Video Link](https://youtu.be/s5dudOrlKBQ)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/33.jpg?raw=true)

With the pads pre-soldered, place the standoff on top of the solder pads with the thinner end facing
downwards.

Place the tip of the iron inside the center of the standoff while gently applying a little force.
After a few seconds you should feel the solder start to liquify and the standoff should move into place.
**Make sure the tip of the iron is clean before placing it inside of the standoff!**

Once it's liquified, place your tweezers on the standoff to keep it from moving and then pull the iron out
from the center.

<!---Video 34b-->
https://user-images.githubusercontent.com/104576748/175935125-5e02e5ea-6c0e-437c-9ab3-1f7589390f49.mp4

[Video Link](https://youtu.be/l3BppBJmHJ4)

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/34.jpg?raw=true)

### Step 8: Board Assembly

The order of which the FR4 plates should go follows
1) Bottom Plate
2) PCB
3) Gasket
4) Top Plate

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/35.jpg?raw=true)

When placing the PCB into the bottom plate, it's going to be a tight fit. You'll more than likely have
to give it a little force. Just be careful with the pcb. Also worth noting, sometimes the Standoffs can be
slightly to one side. In this instance you can reheat the standoff and move it a little to try and center it.

<!---Video 36-->

[Video Link](https://youtu.be/hGnZAwlStW8)

Lastly add the non-slip pads to the bottom of the pcb sliding them through the designated holes in the bottom.

<!---Video 37-->
https://user-images.githubusercontent.com/104576748/175936818-68412787-36c4-42dd-ac92-8cc37cf451cd.mp4

### Step 9: OLED Covers

Screw the OLED standoffs in their designated areas and screw the OLED covers on top.

# CONGRATS YOU'VE COMPLETED ROLLOW!!!

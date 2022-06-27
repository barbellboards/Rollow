# Rollow Build Guide

Rollow is one of the first split keyboards with dedicated thumb encoders... 
It's inspired by the ergonomics of a Ferris and the elegance of a Corne. 
While also influenced by my passion for the automotive customization scene. 

## Parts

It's recommened that before beginning to build Rollow all the necessary parts should be accounted for. 
This insures there aren't any missing pieces in your kit, 
if so please contact Barry (EdgelessCorner#1430 or barbellboards@gmail.com)

| Name | 3x6 | 3x5 | Mini | Excluded From Half Kit |
|:-|:-|:-|:-|:-|
| PCB | 2 | 2 | 2 |  |
| Top plate | 2 | 2 | 0 | x |
| Bottom plate | 2 | 2 | 0 | x |
| Gasket Layer | 2 | 2 | 0 | x |
| EVA Foam | 0 | 0 | 2 | - |
| Oled Covers | 2 | 2 | 2 | x |
| Oleds | 2 | 2 | 2 | x |
| Encoders | 2 | 2 | 2 |  |
| TRRS Jack | 2 | 2 | 2 |  |
| Reset Switch | 2 | 2 | 2 |  |
| Power Switch | 2 | 2 | 2 |  |
| Screws | 18(+2) | 18(+2) | 8(+2) | x |
| Oled Cover Standoffs | 4 | 4 | 4 | x |
| SMD Plate Standoffs | 10 | 10 | 0 | x |
| Kailh Hot Sockets | 40 | 34 | 0 | |
| SMD Diodes | 42(+2) | 36(+2) | 42(+2) | |
| Rubber Pads | 14(+2) | 14(+2) | 0 | x |

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/1.jpg?raw=true)
![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/2.jpg?raw=true)

<sub>*Note: The SMDs in this guide are different from the ones in the Kit.*</sub>

## Building

### Step 1: Deciding on sides

What seems like a trivial step, is fairly important. 
There have been countless mistakes where people have accidentally solder components on the same side for both halfs. Having to desolder SMDs you just soldered isn't fun.

If it makes life easier you can always put a piece of tape depicting what side your Rollows half reperensents.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/3.jpg?raw=true)

### Step 2: Microcontrollers and OLED

This example utilizes socketed mill-max components to socket the microcontrollers and oleds.
It's worth noting that the steps taken are almost identical for non-socketed components. 

Start by using some sort of paper based tape, like painters tape, to tape down your sockets.
The tape serves two purposes

1. The tape helps to keep the sockets from moving when soldering them from the backside of the board.
2. It also stops excess solder from bypassing the throughole on the microcontrollers and binding with the sockets.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/5.jpg?raw=true)

Flip the board around and start by soldering oposite ends of each sockets. Soldering the ends is a simple
way to guarantee the sockets wont move.

Once the ends are soldered you can finish off soldering each individual pins of the sockets.

<sub>*Note: Make sure to double check that each of the pins are soldered correct. 
It's not uncommon to miss a pin and only to realize it aftewards when a full column or 
row of your keyboard isn't working.*</sub>

With the sockets soldered you can begin adding the socketing pins to the sockets. 
When adding the pins it usually takes a little force to seed them properly the first time.

**VIDEO 9**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/10.jpg?raw=true)

Next, you'll need to position the microcontroller on top of the pin. Make sure the microcontroller
is correctl oriented. You can easily check by looking to see if the microcontrollers 
pinout names match those on the pcb.

<sub>*Note: Don't forget to account for the space needed for a Lipo battery under the microcontroller
if you're using a bluetooth setup and you desire the battery posistioned in this manner.*</sub>

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/11.jpg?raw=true)

Continue with soldering the microcontrollers on the board.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/12.jpg?raw=true)

Finish by snipping off any excess of the the pins. 

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/13.jpg?raw=true)

Remove the microcontroller and double check that all the solders look correct.
You can also remove the tape at this step.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/14.jpg?raw=true)

With the microcontroller off you'll have acces to the OLED jumpers. 
Make sure to bridge these jumpers so the OLED is proprely wired to the correct side of the board.  

**VIDEO 15a**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/15.jpg?raw=true)

If you haven't already make sure to complete the soldering of the OLED sockets. 
You can follow the steps above used for socketing the Microcontrollers.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/16.jpg?raw=true)

### Step 3: Reset button, Power Switch, and TRRS

To begin with the reset button, the first thing you'll want to do is pre-solder the through holes.
This will allow for an easier insttallation of the reset switch shown in the video below.

**VIDEO 17**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/18.jpg?raw=true)

With the reset button finished, the next component is the TRRS.
Place the TRRS in the designated area marked on the board.
Then you'll need to flip the board over and solder the pins.

**VIDEO 19**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/20.jpg?raw=true)

Lastly withe the board still flipped with it's bottom facing upward solder the power switch.
Similar to the reset button it's easier to pre-solder one of the switches pads and place the 
switch on top of it.

**VIDEO 21**

### Step 4: Diodes

Instead of soldering each individual SMD at a time, it's easier to do them in a batch like process.
*Make sure you're soldering the SMDs on the front of the board, not the bottom like usual!*
The smds go where the LED lights would within the switches.

Start by soldering one side of each pad.

**VIDEO 24a**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/24.jpg?raw=true)

Holding one end of the diode using a pair of tweezers, slide the diode against the solder 
while heating the solder with the iron. 

**VIDEO xx**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/26.jpg?raw=true)

Finish up by soldering the other ends of the diodes to the board.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/28.jpg?raw=true)

### Step 5: Switch sockets

The sockets use an identical process to the diodes.

Start by pre-soldering one side of the socket's pads.

**VIDEO 29**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/29a.jpg?raw=true)

Place the socket ontop of the with the squared off end facing downward
<sub>*Note: Even though the pcb might show the rounded end facing downward it's best for the 
square end to face downward. If you already soldered it with the round end downward don't worry
about it. There isn't going to be a huge difference in the end. Just makes putting the bottom plate
on easier.*</sub>

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/30a.jpg?raw=true)

Holding one end of the socket with a pair of tweezers, place the soldering iron within the sockets 
"solder valley" holding it untill the solder pases through the valley. 

<sub>*Note: Be careful not to hold the soldering iron on the board for too long*</sub>

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/31.jpg?raw=true)

Lastly, solder the other end of the sockets valley.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/32.jpg?raw=true)

### Step 6: Encoders

The encoders can be a little tricky to work with. There isn't a lot of room to work with
so it's recommended to take your time.

<sub>*Note: Be careful with bending the four pins that are aligned to eachother. They're 
fairly fragile and can snap off fairly easily.*</sub>

Start by bending the farthest outside pin of the encoder just slightly. This step make 
seading the encoder slightly easier.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/22b.jpg?raw=true)

With the pin slightly bent you can sead the encoder into the board. Start by sliding the legs through the 
cylindrical hole in the board. Once the feet are in far enough that they past the bottomm edge of the board 
or are flush. You can gently push the encoder toward you slotting it in place. It might take a little force.

Afterwards you can finish with soldering the pins and bridging the jumpers underneath 

**VIDEO 22**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/22c.jpg?raw=true)

### Step 7: SMD Plate Standoffs

Start by pre-soldering the standoffs pads. Try to to evenly solder around the plate, 
it doesn't have to be perfect. Becareful to not leave the iron on the pads for too long.

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/33.jpg?raw=true)

With the pads pre-soldered place the standoff on top of the pads solder with the thinner end facing
downwards.

Place the tip of the iron inside the center of the standoff while gently applying a little force.
After a few seconds you should feel the solder start to liquify and the standoff should move into place.

Once it's liquified place your tweezers on the stand off to hold it from moving and then pull the iron out 
from the center.

**VIDEO 34**

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/34.jpg?raw=true)

### Step 8: Plate Stacking

The order of which the FR4 plates should go follows
1) Bottom Plate
2) PCB
3) Gasket 
4) Top Plate

![Broken Link](https://github.com/barbellboards/Rollow/blob/main/Instructions/Images/35.jpg?raw=true)

When placing the PCB into the bottom plate it's going to be a tight fit. You'll more than likely have
to give it a little force. Just becareful with the pcb. Also worth noting, sometimes the Standoffs can be 
slightly to one side. In this instance you can rerheat the standoff and move it a little to try and center it.

**VIDEO 36**

Lastly add the non-slip pads to the bottom of the pcb sliding it through the designated holes in the bottom.

### Step 9: Oled Covers

Screw the oled standoffs in their designated areas and screw the oled covers on top.

#CONGRATS YOU'VE COMPLETED ROLLOW!!!


# ISKÄRNA Zigbee Mod

Mod your ISKÄRNA Lamp to connect to Zigbee or Wifi.

![Finished.jpg](images/Finished.jpg)

## Materials and Tools

- [`FUT037Z` Zigbee Controller](https://aliexpress.com/item/1005006638834477.html)
- Wire strippers (or if you don't care about your fingers, a sharp knife)
- Something to cut wires
- Screwdriver

## Opening ISKÄRNA 

Remove the screw at the back.
You will be presented with this
![Disassembly 1.jpg](images/Disassembly%201.jpg)

Remove the screw here so the control board and button-assembly can slide out. It might seem stuck, but you can force it.

![Disassembly 2.jpg](images/Disassembly%202.jpg)
![Disassembly 3.jpg](images/Disassembly%203.jpg)

## Connecting the Zigbee controller

Cut and strip both power and the 4-wired ribbon connecting the head. **The longer the remaining cable length is, the
easier reassembly will be!**

Connect the power wires to the controller

| Terminal | Wire        |
|----------|-------------|
| V+       | Unmarked    |
| V-       | Long dashed |

![Power Wiring.jpg](images/Power%20Wiring.jpg)

Connect the LED wires from the head

| Terminal | Wire         |
|----------|--------------|
| V+       | Unmarked     |
| R        | Short dashed |
| G        | Long dashed  |
| B        | x            |

![RGB Wiring.jpg](images/RGB%20Wiring.jpg)

## Connecting the controller

Cycle the modes (press the "SET" button) of the controller until it is flashing green.
Connect your Zigbee controller and it should show up as `TS0505B`.

## Closing ISKÄRNA

**It will be a tight fit!**

The controller should face "down" (terminal screws facing the back) so the "SET" button can be accessed through the 
empty button hole, angled 45 degrees, slotting in between the rails where the control board and button used to be. The 
power terminals should be at the bottom.


### Additional Images

![PXL_20260325_170834534.MP.jpg](images/PXL_20260325_170834534.MP.jpg)
![PXL_20260325_170906014.MP.jpg](images/PXL_20260325_170906014.MP.jpg)
![PXL_20260325_170916321.MP.jpg](images/PXL_20260325_170916321.MP.jpg)
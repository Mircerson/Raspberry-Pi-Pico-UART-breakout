# Raspberry Pi Pico UART breakout
 A simple 2-layer PCB making the Raspberry Pi Pico a 6 way UART adapter.
 The main purpouse of this board is to be the programmer for the AERQ project which uses UART 0.
<figure>
<img src="Images/3DSimulation.PNG" width="600px">
<figcaption>Figure 1: 3D simulation of the board</figcaption>
</figure>

# Hardware
The board uses six 2.54mm holes for the UART ports and a resistor/LED to indicate the 3v3 bus. 
The board dimensions are: 44.75mm x 55mm 
<figure>
<p align="center">
<img src="Images/Layout.PNG" width="600px">
<figcaption>Figure 2: Layout</figcaption>
</p>
</figure>


# Limits
<b>The maximum output on the 3v3 rail should not exceed ~ 300 mA.</b>

# Software
To make use of all the 6 UART ports available, use [harrywalsh's](https://github.com/ncarandini/KiCad-RP-Pico) software here.
This will make the Pi Pico into a 6 way UART adapter, all the UART ports are marked on the board.


# License
This PCB uses [ncarandini's](https://github.com/ncarandini/KiCad-RP-Pico) footprint for the Raspberry Pi Pico.

# Disclaimer
This project/hardware is provided without warranty, according to the MIT License, and should therefore not be used where it may endanger life, financial stakes, or cause discomfort and inconvenience to others.
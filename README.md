# Quantum3D Obsidian2 Voodoo2 Info

I have luckily obtained TWO Quantum3D Obsidian2 Voodoo2 cards from a kind eBay seller. They were both broken, so I spend a few weeks ionvestigating and fixing them up, plus designing upgrades to enhance its functionalities. I hope my work will help some of you repair and make your Q3D cards work better.

## Mods

I have designed the following mods for this card.
- VGA Input Board
- U21 Xilinx CPLD Replacement
- SLI Bridge. Both rigid & ribbon type

### VGA Input Board

The Q3D card does not come with a VGA input like a retail Voodoo 2 card. However, it has a few pin headers vias on the PCB for that purpose.

I have designed a PCB to plug into those  pin header vias, so you can add a VGA male port, plug in the VGA output of your 2D video card via that Voodoo passthrough cable.


### U21 Xilinx CPLD Replacement
The U21 chip, a Xilinx CPLD, controls mainly sync signals that's output to the VGA output. IF the U21 Xilinx chip on your Q3D card is dead, you won't have any video output on the screen. Sadly, Xilinx chips are well-known to die randomly.

I designed a simple logic circuit to function similarly to the Xilinx CPLD.

*I can tell that the Xilinx CPLD was also doing some signal shaping work, as my replacement outputs a slightly different sized image. But you can easily adjust the monitor to take care of the difference.*

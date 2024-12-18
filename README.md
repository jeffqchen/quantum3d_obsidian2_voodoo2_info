# Quantum3D Obsidian2 Arcade Voodoo2 Info

![q3d_cover](https://github.com/user-attachments/assets/05ede41b-857c-453e-ac4d-8db021c4961f)

I have luckily obtained TWO Quantum3D Obsidian2 arcade Voodoo2 cards from a kind eBay seller. They were both broken, so I spend a few weeks investigating and fixing them up, plus designing upgrades to enhance its functionalities. I hope my work will help some of you repair and make your Q3D cards work better.

## Add-on Projects

I have designed the following mods for this card.
- VGA Input Board
- U21 Xilinx CPLD Replacement
- SLI Bridge. Both rigid & ribbon type
- Protective Armor

### VGA Input Board

<img src="https://github.com/user-attachments/assets/58bd1334-42e6-49d5-985d-173edd2c8a90" width=400> <img src="https://github.com/user-attachments/assets/13575cf6-f5f0-435a-bdb6-092a3f001347" width=400>

The Q3D arcade card does not come with a VGA input like a retail Voodoo 2 card. However, it has a pin header footprint on the PCB for that purpose.

I have designed a PCB to plug into the pin header, so you can add a VGA male port, plug in the VGA output of your 2D video card via that Voodoo passthrough cable.

### U21 Xilinx CPLD Replacement

<img src="https://github.com/user-attachments/assets/030cd0b4-02d7-48d7-902c-469b66753450" width=400> <img src="https://github.com/user-attachments/assets/c4a8ca3c-9be2-410e-8c31-d44b522985e0" width=400>

The U21 chip, a Xilinx CPLD, controls mainly sync signals that's output to the VGA output.

There seems to be a few situations wit this chip.
- Some arcade boards come with a security setup and this chip won't function as-is.
- Sometimes this Xilinx chip dies, and you won't have any video output on the screen.

Both situations will render the card useless. I designed a simple logic circuit to function similarly to the unlocked Xilinx CPLD.

### SLI Bridge

<img src="https://github.com/user-attachments/assets/38528fac-02f9-4fe8-ab6e-efcf25808933" width=400> <img src="https://github.com/user-attachments/assets/a1d1aeb0-7cc8-45bd-b164-772cb0be827b" width=400>

This card can do SLI! However you need to add in a few missing components before that. With that part taken care of, I've come up with a rigid SLI bridge board that helps you SLI two of these same cards, or with a reference card. The info on how to create a ribbon type cable will also be available.

### Protective Armor

This set of 3D printed armor will protect sensitive SMD components and improve handling of the card, while making the card look way more nicer. It wouldn't hurt to try!

<img src="https://github.com/user-attachments/assets/af98fcf5-9f91-443a-86ff-7620e5b8ce7f" width=800>

<img src="https://github.com/user-attachments/assets/5acdf2c2-59ed-45ab-a19a-b28eb07354d5" width=400> <img src="https://github.com/user-attachments/assets/aec538a6-b814-4a80-8c75-c7a4bf7223b6" width=400>

## Mods

<img src="https://github.com/user-attachments/assets/192f9c04-e282-4070-932b-58050707038c" width=400> <img src="https://github.com/user-attachments/assets/3af62eb1-be3f-4528-b8f6-8422dec971e4" width=400>

Solder on 2MB of EDO RAM chips to the FBI on the back of the card to make it a 12MB Voodoo 2.

<img src="https://github.com/user-attachments/assets/bd46c42e-08ad-42f8-877d-4963a9ce8127" width=400> <img src="https://github.com/user-attachments/assets/1b821c5d-acbf-4553-b906-aa1b4b854db4" width=400>

Restore picture brightness to the full PC standard.

All information is available in the [Project Wiki](https://github.com/jeffqchen/quantum3d_obsidian2_voodoo2_info/wiki) pages.

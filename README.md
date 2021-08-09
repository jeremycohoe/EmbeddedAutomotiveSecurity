# EmbeddedAutomotiveSecurity

This training is geared towards offensive security researchers, penetration testers or red teamers who want to dip their toes into the field of automotive security. The basis of this training are developments boards that give the attendees a practical introduction to bus systems such as CAN, LIN and FlexRay. After the students have learned about common ECU classes, protocols and the AUTOSAR standards we will write some parts of an ECU ourselves to put us in the position of a developer. We then switch to an offensive security perspective and take apart and analyse an ECU image step by step until we will have (a) working exploit(s) against that system at the end of the week.

In contrast to other trainings, we will not look into infotainment units as we see them as too similar to other embedded and mobile systems. Rather we will concentrate on the specifics of automotive embedded systems. To help with this process we will show the attendees how to snapshot and emulate systems to be faster in assessing them.

## Session 0

* Classes of ECUs in cars
* Protocols in use in cars
* [Exercise #0: Hypothesising potential vulnerabilities by reading standards](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise0.md)
* Automotive network topologies
* Exercise #1: Test communications with an ECU
* Q&A / Wrap-up Session 0

## Session 1
* AUTomotive Open System ARchitecture (AUTOSAR) Basics
* [Exercise #2: Build your own ECU firmware (using S32 Design Studio)](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise2.md) 
* Obtaining ECU firmware and memory
* [Exercise #3: Use JTAG to snapshot a device for emulation](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise3.md) 
* Speeding up your analysis using emulation
* [Exercise #4: Disassemble a ECU flash image](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise4.md)
* Q&A / Wrap-up Session 1

## Session 2 

* Detailed explanation of I2C, CAN, CAN-FD and LIN buses
* [Exercise #5: Reverse engineering functionality and finding bugs](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise5.md) 
* Automotive Ethernet, Gateways and Ethernet switches as isolators
* [Exercises #6: Mapping and understanding attack surface](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise6.md) 
* Q&A / Wrap-up Session 2

## Session 3

* Attack planning/Chaining vulnerabilities
* [Exercises #7: Reverse engineering functionality and finding bugs (continued)](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise7.md)
* FlexRay
* [Exercise #8: FlexRay](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise8.md)
* Q&A / Wrap-up Session 3

## Session 4
* Real-world car hacking: How to source parts, how not to tear apart your car, where to find documentation and tools
* [Exercise #9: Understanding and doodling schematics](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise9.md)
* Building benches and labs
* [Exercise #10: Exploiting the bugs you found](https://github.com/Merimetso-Code/EmbeddedAutomotiveSecurity/blob/main/Exercise10.md)
* Q&A / Final Wrap-up

## Development Details

The development board that we are going to be using for this class is the NXP MPC5748G Development Board. Information about this board can be located at the following URL:

* https://www.nxp.com/design/development-boards/automotive-development-platforms/mpc57xx-mcu-platforms/mpc5748g-development-board-for-secure-gateway:DEVKIT-MPC5748G 

The following is an image of the MPC5748G Development board that we are going to use in this class
![MPC5748G](DEVKIT-MPC5748G-BD.jpg)

It is expected that all students have a latop/computer running an up to date version of the Microsoft Windows 10 Operating System.

## Contact Details

For further information and questions please contact Dr Andrew Blyth, PhD. <ablyth@merimetso.net>

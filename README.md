# AndromedaFlightComputer
Flight computer developed for the solid rocket Osprey, flown at the Spaceport America Cup in 2022

# Design Description: 

A modular approach to rocket avionics featuring a STM32-based flight computer interfacing with a 900MHz radio, GNSS Module, 9-axis IMU, barometer, flash storage, audio system, wired ground system communication (RS232), analog pressure transducer inputs, debug system. The flight computer is broken into three distinct components: power management board, engine communication board, and data management board. The components are secured via screw mounts, which allows for easy replacement in the field. 

The data management board is a four layer PCB with careful power planes designed to accomodate and control 3A of power to facilitate downstream avionics. A large capacitor is included to protect during brownouts that may occur during high acceleration events. 
![alt text](https://github.com/rwjmoore/AndromedaFlightComputer/blob/fe1f59382d7c7989c939c095f7d0d2cb6e69b2e5/DMB_Top.jpg)


![alt text](https://github.com/rwjmoore/AndromedaFlightComputer/blob/80b1837258c016f6d01d0e591765dae2840442b2/DMB_stack.jpg)



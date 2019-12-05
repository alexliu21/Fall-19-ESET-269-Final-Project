# Fall-19-ESET-269-Final-Project
Final project for ESET 269 at Texas A&M University, Fall 2019

Contributors:

- Kristopher Elers (UI design, RGB Control, Functions)
- Alex Liu (RGB Control, Digital Input)
- Maksym Sury (RGB Control, Digital Input, Temperature Reading)

This project was written in C using Keil µVision IDE and requires Teraterm (Baud Rate: 115200) and a MSP432P401R Launchpad.  Menu option 3 requires a temperature sensor on a breadboard with jumper wires hooked up to P5.4 with power running to a 3.3V connector and grounded at the ground connector underneath the 5V pin on the MSP432 Launchpad.  Ensure that your circuit is correct before connecting the power.  The temperature sensor will overheat if it's incorrect and could destroy the MSP432.

The program UI will display:

MSP432 Menu

  1. RGB Control
  2. Digital Input
  3. Temperature Reading
  4. Quit

- Selecting option 1 will prompt the user for an RGB value (1-7), a toggle time, and a number of blinks.  It will then blink the LED the desired color, with the desired delay, the desired amount of times.
- Selecting option 2 will print the current button(s) that are held down.  Please hold the button(s) down BEFORE pressing enter.
- Selecting option 3 will ask the user for a number of temperature readings (1-5) to perform and will print the temperature that the temperature sensor is reading in both Celsius and Fahrenheit.
- Selecting option 4 will stop the program.

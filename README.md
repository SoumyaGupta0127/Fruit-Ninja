# FPGA Fruit Ninja

Fruit Ninja is a popular mobile game that involves slicing different types of fruits with a finger swipe. In this project, we implemented a hardware-based version of Fruit Ninja using an FPGA board. This project aims to create a unique and interactive game that showcases the capabilities of FPGA technology.

## Development Process

The game was divided into smaller parts, implemented individually as modules. After proper simulations and testing, the modules were integrated together to make the game. This approach allowed us to work efficiently and enables us to upgrade and modify the game easily later.

## Methodology

For input, we are using a joystick. The joystick gives an analog output depending on its position, which we convert to a digital signal using the FPGA's onboard ADC. We are displaying our output on a monitor using VGA. The entire project was written in Verilog, and was implemented on an FPGA board - Nexys A7 100T.

## Results

A simplified, working version of Fruit Ninja was implemented on an FPGA. The game starts with one fruit on the screen, the number increases as the player plays the game. The game ends if the player misses too many fruits, or if they reach the maximum number of fruits to be cut. For cutting the fruits, the player controls a cursor on-screen using a joystick.

## Impact

This project demonstrates the high-speed and low-latency capabilities of FPGAs. It also shows the flexible computational ability of FPGAs, with significantly low power consumption.

## Future Goals

We plan to improve the graphics for the game by implementing more realistic fruits, better background, and cutting animations. We also plan to add some more gameplay mechanics, like bombs. As our design may not be optimized, we plan to modify it to make it more fast and efficient.

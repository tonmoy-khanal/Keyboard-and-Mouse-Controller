# Keyboard-and-Mouse-Controller

## Overview

This project demonstrates the integration of the Mouse and Keyboard libraries to create a versatile input controller. Five momentary switches act as directional buttons for your cursor. When a button is pressed, the cursor on your screen will move, and a keypress, corresponding to the letter associated with the direction, will be sent to the computer. It's a fun and interactive way to control your computer's cursor and input text.

## Hardware Requirements

To build and use this controller, you'll need the following hardware components:

- Arduino Leonardo, Micro, or Arduino Due board
- 5 pushbuttons
- 5 10k ohm resistors
- Hook-up wires
- Breadboard

## Software Requirements

To program and run the controller, you'll need the Arduino IDE, which you can download from the official Arduino website.

## Circuit Setup

Follow these steps to set up the circuit:

1. Attach one end of the pushbuttons to pins 2, 3, 4, 5, and 6 on the Arduino board.
2. Attach the other end of the pushbuttons to +5V.
3. Use the 10k ohm resistors as pull-down resistors by connecting them from the pins connected to the board to ground.

## Usage

Once you've programmed your Arduino board using the provided code, unplug the USB cable and open a text editor or any application where you want to control the cursor and input text. Connect your board to your computer and press the buttons to interact with the document as you move the cursor.

## Contribution

If you have any questions, doubts, or want to contribute to this project, feel free to reach out to us at [www.tonmoykhanal.tech](https://www.tonmoykhanal.tech). We welcome contributions and feedback from the community to improve and expand the capabilities of this controller.

## Author

This project is authored by Tonmoy Khanal. You can learn more about the author and explore additional projects on their website: [www.tonmoykhanal.tech](https://www.tonmoykhanal.tech).

Enjoy controlling your computer with this creative Arduino-based Keyboard and Mouse Controller!

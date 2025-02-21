# MagTag-In-Office
Use your MagTag as an office door status sign. Let them know if you are out to lunch.
![InOffice](https://github.com/user-attachments/assets/28fe19ab-4694-40fb-9e81-1cf6b435be5b)
MagTag Office Status Display

This project is designed for the Adafruit MagTag ePaper display. It provides a simple office status indicator, allowing quick updates on your availability using MagTag's built-in buttons.

Features

Displays current status ("In Office", "Out of Office", "Back in 15 min", "Out to Lunch", "Gone rest of day").

Updates status using MagTag's buttons (A, B, C, D).

Clear and readable text display.

Uses ePaper technology for low-power status retention.

Hardware Requirements

Adafruit MagTag

USB-C cable for programming

Installation

Install CircuitPython on your MagTag.

Download the latest Adafruit CircuitPython MagTag library bundle.

Copy the required libraries into the lib/ directory on your MagTag.

Copy the provided Python script (code.py) to the root of your MagTag.

Usage

Button A: Toggles between "In Office" and "Out of Office".

Button B: Sets status to "Back in 15 min".

Button C: Sets status to "Out to Lunch".

Button D: Sets status to "Gone rest of day".

The status remains on the screen even after power-off, thanks to ePaper technology.

How It Works

The script initializes the MagTag and sets up text fields.

Default status is "In Office".

Button presses update the status display.

The screen refreshes with the new status.

A small delay prevents unnecessary processing load.

Example Screenshot

(You can add an image here showing the MagTag displaying a status.)

License

This project is open-source under the MIT License.

Credits

Developed using Adafruit CircuitPython and MagTag libraries.

For any issues or improvements, feel free to submit a pull request or open an issue in this repository.

# Clap-Counter-Project
8051 microcontroller project for counting claps using a clap sensor.


# Clap Counter Project

This project uses an 8051 microcontroller and a clap sensor to count claps hands-free. The clap is detected through a condenser mic, and the count is displayed on an LCD. This project is useful for applications requiring hands-free counting, such as attendance systems or traffic monitoring.

## Features:
- Clap detection using condenser mic
- Real-time count display on an LCD
- Overflow handling for counts above 99

## Components:
- 8051 microcontroller
- Clap sensor (condenser mic)
- LCD display

## Working:
- The clap sensor sends a signal to the microcontroller.
- The microcontroller debounces the signal and increments the count.
- The count is displayed on the LCD, and the system handles overflow (resets after 99 claps).

## How to Run:
1. Flash the provided code onto the 8051 microcontroller.
2. Connect the components as per the provided circuit diagram.
3. Clap near the sensor to see the count increment on the display.

## Video Demonstration
You can find a video demonstration of the working Clap Counter in the following link: [Video Link]

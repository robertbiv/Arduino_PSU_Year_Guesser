# Arduino PSU Year Guesser

An interactive Arduino project that challenges users to guess the founding year of Penn State University using various electronic components including LEDs, buzzers, LCD display, and potentiometers.

## Overview

This mini test demonstrates Arduino programming fundamentals through a fun guessing game about PSU's founding year. The project showcases hardware interfacing, user input handling, visual feedback through LEDs, audio output via buzzer, and information display on an LCD screen.

## Project Description

The PSU Year Guesser is an educational Arduino project that combines multiple hardware components to create an engaging user experience. Players interact with the system using potentiometers to input their guess for when Penn State University was founded, receiving immediate feedback through LEDs, sound, and LCD messages.

## Hardware Components

- **Arduino Board**: Microcontroller for project logic
- **Breadboard**: Circuit prototyping platform
- **LED Lights**: Visual feedback indicators
- **Passive Buzzer**: Audio feedback for correct/incorrect guesses
- **LCD Display**: Shows instructions, feedback, and game information
- **Potentiometers**: User input controls for year selection
- **Jumper Wires**: Component connections
- **Resistors**: Current limiting for LEDs

## Features

- Interactive year guessing gameplay
- Real-time feedback via LEDs and buzzer
- LCD display for instructions and results
- Potentiometer-based input for year selection
- Visual and audio cues for correct/incorrect answers
- Educational introduction to Arduino programming

## Technology Stack

- **C++ (100%)**: Arduino programming language
- **Arduino IDE**: Development environment
- **Hardware Interfacing**: Digital and analog I/O
- **LCD Library**: Display control

## Circuit Design

The project utilizes standard breadboard prototyping techniques with:
- Digital pins for LED control
- PWM output for buzzer control
- Analog input for potentiometer reading
- I2C or parallel interface for LCD communication

## How to Use

### Hardware Setup
1. Gather all required components listed above
2. Follow the circuit diagram (refer to project documentation)
3. Connect components to the breadboard according to pin assignments in code
4. Ensure all connections are secure

### Software Setup
1. Install Arduino IDE from [arduino.cc](https://www.arduino.cc/)
2. Clone or download this repository
3. Open `Hackathon.ino` in Arduino IDE
4. Select your Arduino board type under Tools > Board
5. Select the correct COM port under Tools > Port
6. Upload the sketch to your Arduino

### Playing the Game
1. Power on the Arduino after uploading the code
2. Read the instructions on the LCD display
3. Adjust the potentiometer to select your guess
4. Submit your answer (method depends on code implementation)
5. Observe the LED and buzzer feedback
6. Try again if incorrect, celebrate if correct!

## Learning Outcomes

- Arduino programming fundamentals
- Digital and analog I/O operations
- LCD display interfacing
- Hardware component integration
- User interaction design
- Circuit design and breadboarding
- Sensor input processing

## Penn State Trivia

**Answer**: Penn State University was founded in 1855 as the Farmers' High School of Pennsylvania, later becoming the Pennsylvania State College in 1874, and finally Pennsylvania State University in 1953.

## Author

**Robert Bennethum IV** ([robertbiv](https://github.com/robertbiv))

## License

This project is available for educational purposes.

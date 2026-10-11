# Modular Arduino & ESP32 Embedded Labs

A practical collection of modular embedded systems experiments using **Arduino and ESP32** microcontrollers. This repository is designed for students, beginners, and technology enthusiasts to learn electronics, sensor interfacing, embedded programming, and IoT development through hands-on projects.

## Components

Components depend on the individual lab or experiment. Common examples include:

* Arduino Uno and ESP32 development boards
* Sensors and input modules
* LEDs, buzzers, motors, and other output devices
* Breadboard and jumper wires
* Resistors and supporting electronic components
* USB cable and suitable power supply

**Note:** Refer to each experiment's component list before assembling its circuit.

## Pin Connections

Pin connections vary by experiment and microcontroller.

Each lab should include its own pin-mapping table identifying the component, signal pin, and corresponding Arduino or ESP32 GPIO.

**Important:** Arduino Uno and ESP32 use different voltage levels and pin capabilities. Verify compatibility before connecting modules.

## How It Works

1. Select an experiment from the repository.
2. Review its components and circuit connections.
3. Connect the components to the appropriate microcontroller pins.
4. Upload the corresponding program using the Arduino IDE.
5. Observe the inputs, outputs, sensor readings, or communication behavior.
6. Modify the program and experiment with different values to understand the underlying concepts.

## Software Requirements

* Arduino IDE
* Appropriate Arduino board support package
* ESP32 board package when working with ESP32
* USB drivers, if required by the development board
* Additional libraries specified by individual experiments

## Setup Instructions

1. Clone or download this repository.
2. Open the folder for the experiment you want to run.
3. Install the required board package and libraries.
4. Connect the correct development board to your computer.
5. Select the board and COM port in Arduino IDE.
6. Verify the pin connections and upload the code.
7. Open Serial Monitor if the experiment uses serial output.

## Project Status

* **Source Code: [Modular Arduino & ESP32 Embedded Labs.docx](https://github.com/user-attachments/files/33309125/Modular.Arduino.ESP32.Embedded.Labs.docx)

* **Circuit Diagrams:<img width="680" height="680" alt="Modular Arduino   ESP32 Embedded Labs" src="https://github.com/user-attachments/assets/3ad871fc-152f-4804-a18d-623e5ca02f0d" />

* **Hardware Testing Videos:

https://github.com/user-attachments/assets/3d30c598-c5d2-4b6f-a55e-d0cfc5b89b3f



## Safety Note

* Disconnect power before changing circuit connections.
* Check voltage and current requirements for every component.
* ESP32 GPIO pins operate at 3.3V logic and are generally not 5V tolerant.
* Use suitable driver circuits for motors, relays, and other high-current loads.
* Never connect mains-voltage appliances directly to a microcontroller. Mains projects require properly rated isolation and qualified supervision.

## Author

**Imran Khan**
IT, IoT & Digital Solutions Professional

* **GitHub:** https://github.com/Imran-khan009
* **Portfolio:** https://sengrimrankhan.netlify.app

---

*Built for practical learning in Arduino, ESP32, embedded systems, and IoT.*

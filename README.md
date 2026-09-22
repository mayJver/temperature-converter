# Absolute Zero Temperature Converter

![OS: Linux](https://img.shields.io/badge/OS-Linux-orange)
![Environment: Gambas 3](https://img.shields.io/badge/Environment-Gambas%203-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

A desktop graphical user interface (GUI) application built with Gambas 3 that provides real-time temperature conversions across Fahrenheit, Celsius, Kelvin, and Rankine scales. The system features dynamic slider synchronization and strict mathematical validation to prevent calculations below absolute zero.

## Key Features

* **Real-Time Conversion:** Instantly calculates values across four distinct thermodynamic scales upon input.
* **Absolute Zero Validation:** Includes strict logical barriers that prevent the user from entering physically impossible temperatures (e.g., values below -273.15 °C or 0 K), alerting the user and halting the conversion.
* **Synchronized UI:** Two-way data binding between text inputs (ValueBoxes) and interactive sliders.
* **Dynamic Range Adjustment:** Users can expand or reduce the maximum limits of the sliders on the fly to calculate extreme temperatures.

## Prerequisites

To run or compile this project, you need a Linux environment with the Gambas 3 framework installed.

* [Gambas 3](http://gambas.sourceforge.net/en/main.html)
* GTK+ or Qt libraries (handled automatically by the Gambas IDE)

## Installation and Execution

**Option A: Running from the IDE (Recommended for review)**

1. Clone the repository:
   ```bash
   git clone https://github.com/mayJver/temperature-converter.git
   ```
3. Open the Gambas 3 IDE.

4. Select Open project and navigate to the cloned directory.

5. Press F5 to run the application.

**Option B: Running from Terminal (If compiled)**

If you wish to compile it into a standalone executable archive:
```bash

gbc3 -a
gba3
./temperature-converter.gambas
```
## Architecture Notes

The application implements strict variable typing and Hungarian notation for GUI elements to maintain clean, readable code. Internal variables are encapsulated (Private), ensuring predictable lifecycle states across form interactions.

## Authors

    Ismael González Díaz Leal

    Annel Monserrat Guadarrama Trujillo

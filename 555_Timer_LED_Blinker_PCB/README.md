# 555 Timer LED Blinker PCB Project

My second KiCad PCB design project based on the classic NE555 timer IC in astable mode.

This circuit continuously blinks an LED using RC timing components and demonstrates the basics of analog timing circuits, oscillators, and PCB layout design.

---

## Features

- NE555 timer IC based LED blinker
- Adjustable blinking speed using potentiometer
- Through-hole components
- ERC verified schematic
- DRC verified PCB layout
- Gerber and drill files generated
- Beginner-friendly analog electronics project

---

## Circuit Description

The NE555 timer is configured in astable mode, where the timing capacitor continuously charges and discharges through resistors.

This creates a square wave output at pin 3 of the 555 timer, which turns the LED ON and OFF repeatedly.

The potentiometer changes the charging/discharging time of the capacitor, allowing adjustable blinking speed.

---

## Components Used

| Component | Value |
|---|---|
| NE555 Timer IC | DIP-8 |
| R1 | 22kΩ |
| RV1 | 100kΩ Potentiometer |
| R2 | 470Ω |
| C1 | 1µF Electrolytic Capacitor |
| C2 | 0.01µF Ceramic Capacitor |
| LED | Standard 5mm LED |
| Power Supply | 9V Battery |

---

## Tools Used

- KiCad 10
- GitHub

---

## Learning Outcomes

This project helped me learn:

- Schematic capture in KiCad
- PCB routing and placement
- Footprint assignment
- ERC and DRC validation
- Gerber file generation
- Analog timing circuit basics
- 555 timer operation

---

## Project Outputs

- Schematic completed
- PCB layout completed
- ERC passed
- DRC passed
- Gerber files generated
- Drill files generated

---

## Future Improvements

- Add power switch
- Add multiple LEDs
- Add frequency calculation labels
- Use SMD components
- Design compact PCB version

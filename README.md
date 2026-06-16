# 9V to 5V Buck Converter

A custom-designed buck converter that steps a 9V input down to approximately 5V using discrete components.

## Overview

The goal of this project was to design, simulate, and prototype a buck converter while gaining a deeper understanding of switching power supplies, PWM control, MOSFET gate driving, and LC filter design.

## Design Process

1. Calculated component values using buck converter design equations and circuit analysis techniques.
2. Designed and simulated the converter in LTspice.
3. Generated a PWM signal using an Arduino.
4. Implemented a discrete totem-pole gate driver to improve MOSFET switching performance.
5. Built and tested the circuit on a breadboard.

## Results

- Input Voltage: 9V
- Target Output Voltage: 5V
- Initial Output Voltage: ~2.9V
- Improved Output Voltage: ~4.7V
- Simulation closely matched hardware performance.

## Challenges

- High-side N-channel MOSFET gate drive limitations
- Output voltage regulation
- Inductor current ripple analysis
- Gate driver thermal issues

## Components Used

- RFP30N06LE MOSFET
- 1N5819 Schottky diode
- Inductor
- Capacitor
- Arduino Uno
- S8550 PNP transistor
- 2N7000 MOSFET

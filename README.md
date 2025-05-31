# SCR Controller – R&D Project
Precise gate control system for 6 high-power SCR channels using a Microcontroller PWM with opto-isolated trigger circuit.

## Overview
This project develops a programmable gate pulse controller for SCRs used in magnetic particle inspection (MPI) machines. It provides isolated, high-current gate pulses using an isolated PWM, low pass filter, and power op-amp stage, enabling safe, flexible SCR firing control.

Applications:
- Non-destructive testing
- High-current industrial power stages

## Key Features
- PWM-based gate pulse generation (10–80 µs pulse width)
- Up to 10V and 1000 mA opto-isolated gate driver
- Configurable pulse width and delay
- LCD Diagnostics Display
- Powered from 240V - 480V DC Range

## Getting Started

### Hardware Setup
- Connect board's 6 SCR channels to respective gate and anode
- Connect energize button and input signal
- Connect to 240V - 480V power source

### Firmware Notes
- `main.c` sets up SPI and gate pulse logic
- Pulse parameters are hardcoded for now (change in `config.h`)

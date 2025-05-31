# Project Log: SCR Controller

## 05-08-2025 - Meeting Summary
- Revised prototype design, Block diagram of overall system made
    - System leverages MCU + PWM combination to control 6 SCRs
- Looking for boards to be modular
- one board handles 12 SCRs (6 pairs of SCRs. Paired in parallel), adding another handles another 6 maybe 3rd smaller different board to control multidirectional.

## 2025-05-20 – Meeting Summary
- Opto-isolated trigger confirmed
- Gate pulse duration: 80 µs + 10V spike, then hold at 4V
- I’ll test DAC-OpAmp gate driver by Friday
[Full Notes on Notion](https://...)

## 2025-05-19 – Lab Notes
- SPI DAC output is stable
- Gate test failed at low voltage — suspect timing mismatch

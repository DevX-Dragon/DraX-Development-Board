# DraX Development Board
A compact, high-performance development board based on the RP2040 microcontroller, designed for versatility with dual power options and easy breadboard integration.

## Layouts
<img width="295" height="540" alt="PCB Layout" src="https://github.com/user-attachments/assets/44966b50-7e44-4a7a-8983-99a7db1ad568" />

<img width="600" height="540" alt="Schematics Layout" src="https://github.com/user-attachments/assets/db2badd6-0481-4439-8cdc-2a6ad9abbad0" />

## Renders
<img width="240" height="240" alt="front view" src="https://github.com/user-attachments/assets/85d07ea6-249b-4283-8d91-97f368ac72ab" />
<img width="240" height="240" alt="Front" src="https://github.com/user-attachments/assets/2b4eb931-7418-4ad7-b1b2-92fc2589f694" />
<img width="240" height="240" alt="back" src="https://github.com/user-attachments/assets/c40f0b95-14d9-44cb-a8cd-f8264af25a9b" />
<img width="170" height="170" alt="side" src="https://github.com/user-attachments/assets/4431caa4-42e0-4fda-9a71-35057bfc1c9c" />


## Technical Specifications

**Microcontroller:**
Raspberry Pi RP2040 dual-core ARM Cortex-M0+.

**Storage:** 
16MB (128Mbit) QSPI Flash memory (W25Q128).

**Power Input:** 
Dual-power path with Schottky diode protection (D1, D2).

**USB-C:**
5V via 14-pin USB-C receptacle.

**Battery:**
JST-style connector for LiPo battery support.

**Regulation:**
On-board LDO regulator (NCP1117) providing stable 3.3V.

**Clock:**
12MHz crystal oscillator with 15pF load capacitors.

**I/O:**
40-pin total breakout via dual 20-pin headers (J2, J3) including GPIO and ADC.

**Debugging:**
Dedicated SWD (Serial Wire Debug) header (J4).

**User Interface:**
Tactile Push-buttons for Reset and BOOTSEL modes.

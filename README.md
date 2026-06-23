# Microcontrollers in Smart Systems

> PIC microcontroller labs and a team-built active noise-canceling system prototype

![C (XC8)](https://img.shields.io/badge/C_%28XC8%29-0a7?style=flat-square) ![MPLAB X IDE](https://img.shields.io/badge/MPLAB_X_IDE-0a7?style=flat-square) ![PICKit3](https://img.shields.io/badge/PICKit3-0a7?style=flat-square) ![PIC16F887](https://img.shields.io/badge/PIC16F887-0a7?style=flat-square) ![PIC16F917](https://img.shields.io/badge/PIC16F917-0a7?style=flat-square) ![MIKROE-2859 microcontroller](https://img.shields.io/badge/MIKROE--2859_microcontroller-0a7?style=flat-square) ![SPI](https://img.shields.io/badge/SPI-0a7?style=flat-square) ![UART](https://img.shields.io/badge/UART-0a7?style=flat-square) ![I2C](https://img.shields.io/badge/I2C-0a7?style=flat-square) ![MCP6S26 (GAINAMP2) PGA](https://img.shields.io/badge/MCP6S26_%28GAINAMP2%29_PGA-0a7?style=flat-square) 

### 🌐 Live project page → **https://selsaady1.github.io/egr338-microcontrollers-smart-systems/**

## Overview
Coursework from ASU's EGR 338 (Microcontrollers in Smart Systems, Spring 2024) covering hands-on PIC embedded programming labs and a capstone design project. The labs progress through flashing LEDs and combinational logic, the comparator module, UART/SPI/I2C serial communication between PIC16F917 and PIC16F887 microcontrollers, and a programmable digital-potentiometer-driven 555 timer oscillator. The final project, built by the six-member Team A.I (Acoustic Innovators), is an active Noise Canceling System (NCS) prototype that captures audio, processes it on a PIC-based microcontroller, and outputs a noise-reduced signal.

## Key Achievements
- Co-developed an active Noise Canceling System prototype on a MIKROE-2859 microcontroller, pairing an MCP3526 ADC, CMA-4544PF-W microphone, MAX98363 audio amplifier, and a speaker for real-time audio processing
- Authored the project research, technical report, and presentation deck, and documented a costed bill of materials with itemized component prices
- Programmed software-controlled gain and channel selection on the MCP6S26 (GAINAMP2) programmable-gain amplifier over SPI from the PIC microcontroller, with working SPI master C code in the report appendix
- Implemented UART serial communication (uart.h driver, 9600 baud) between a PIC16F917 transmitter and PIC16F887 receiver, plus demonstrated SPI and I2C links verified on oscilloscope
- Completed comparator-module, combinational-logic/flashing-LED, and DS1804-100 digital-potentiometer plus 555-timer astable oscillator labs in C using MPLAB X IDE, the XC8 compiler, and a PICKit3 programmer

## Approach
Embedded firmware was written in C and flashed to PIC16F887/PIC16F917 microcontrollers using MPLAB X IDE, the Microchip XC8 compiler, and a PICKit3 in-circuit programmer, with circuits prototyped on breadboards and signals verified on a Digilent Analog Discovery board and oscilloscope. The NCS final project followed a structured design process: rationale and engineering goals, two evaluated design alternatives, final schematic selection, and a defined testing protocol of calibration, frequency-response sweep, and ambient-noise simulation. Saif's role centered on research and producing the report and presentation while teammates handled circuit construction and testing, all within an 8-week project timeline.

## Tools & Technologies
- C (XC8)
- MPLAB X IDE
- PICKit3
- PIC16F887
- PIC16F917
- MIKROE-2859 microcontroller
- SPI
- UART
- I2C
- MCP6S26 (GAINAMP2) PGA
- MCP3526 ADC
- DS1804-100 digital potentiometer
- 555 timer
- Digilent Analog Discovery / oscilloscope

## Repository Structure
```
.gitignore
LICENSE
README.md
docs/555_Pins_Value_Table.docx
docs/Code_C.docx
docs/EGR338_Powerpoint_3_.pdf
docs/EGR338_Report_3_.pdf
docs/Laboratory_1.19_Week_1_Flashing_LED_s_Combinational_Logic.docx.pdf
docs/Laboratory_2.19_Week_3_Comparators.docx
docs/Laboratory_3.19_Week_6_True_Correct_UART_Slave_RX_PIC16F887_C-Code.doc
docs/Laboratory_3.19_Week_6_True_Correct_uart.h_C-Code.docx
docs/Laboratory_3.19_Week_6_UART_SPI_I2C.docx
docs/Laboratory_4.19_Week_11_Digital_Potentiometer.docx
images/IMG_20240207_153908.jpg
images/IMG_20240207_153912.jpg
images/IMG_20240207_154121_1_.jpg
images/IMG_20240207_155102.jpg
images/image0.jpeg
images/image2.jpeg
src/Laboratory_3.19_Week_6_True_Correct_UART_Master_TX_PIC16F917_C-Code.do
```

## Results
The NCS prototype was delivered as a working breadboard system documented in a 22-page report and presentation, and each lab was demonstrated and signed off with oscilloscope-verified serial-communication waveforms; see docs/EGR338_Report_3_.pdf for the full design write-up.

## Deliverable
See [`docs/EGR338_Report_3_.pdf`](docs/EGR338_Report_3_.pdf).

## License
MIT — see [`LICENSE`](LICENSE).

---
_Part of [Saif Elsaady's engineering portfolio](https://selsaady1.github.io/portfolio/). Deliverables only — routine homework/quizzes/exams excluded._
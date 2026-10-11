# STM32 SPI Interface with ILI9341 TFT Display

## Project Overview
This project simulates hardware-level **Serial Peripheral Interface (SPI)** communication between an **STM32 Nucleo-C031C6** board and an **ILI9341 Color TFT LCD Display** using Wokwi. 

It demonstrates how to transfer control signals and text data to drive an external graphics display, making it a useful reference for embedded hardware interface design.

## Live Simulation
You can run and test the interactive circuit directly in your web browser:
-> Run Wokwi Simulation: wokwi.com/projects/470371125974512641

## Key Specifications
* Microcontroller: STM32 Nucleo-C031C6.
* Display Controller: ILI9341 TFT LCD Driver.
* Communication Protocol:Serial Peripheral Interface (SPI).
* Dependencies:  `Adafruit_GFX` and `Adafruit_ILI9341`.

**  Repository Structure
- `sketch.ino` — Core microcontroller source code.
- `diagram.json` — Wokwi circuit schematic and pin connections.
- `libraries.txt` — Project library dependencies.
- `wokwi-project` — Simulation configuration file.

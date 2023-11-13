![Profile Views](https://komarev.com/ghpvc/?username=Veolinan&color=brightgreen)

# RFID Test using ESP8266 and MFRC522

This repository contains a simple Arduino sketch for testing RFID functionality with an ESP8266 microcontroller and the MFRC522 RFID module. The code is designed to interface with the MFRC522 library, making it easy to integrate RFID capabilities into your ESP8266 projects.

## Hardware Requirements
- ESP8266 microcontroller (NodeMCU)
- MFRC522 RFID module
- Jumper pins
- USB cable

## Pin Connections
- MFRC522 SDA pin to D2
- MFRC522 SCK pin to D5
- MFRC522 MOSI pin to D7
- MFRC522 MISO pin to D6
- MFRC522 RST pin to D1
- MFRC522 SDA pin to D8
- MFRC522 3.3V to 3V3 on ESP8266
- MFRC522 GND to GND on ESP8266

## Setup
1. Connect the MFRC522 module to the ESP8266 following the provided pin definitions.
2. Install the necessary libraries (MFRC522 and SPI) using the Arduino Library Manager.
3. Upload the sketch to your ESP8266 board.

## Usage
1. Open the Serial Monitor to view the detected RFID card's UID when presented to the RFID module.
2. Customize the code to fit your specific project requirements.

Feel free to use and modify this code as a starting point for incorporating RFID functionality into your ESP8266-based projects. If you encounter any issues or have suggestions for improvement, please contribute to the repository.

[![License](https://img.shields.io/github/license/Veolinan/RFID_NodeMCU-ESP-8266)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/Veolinan/RFID_NodeMCU-ESP-8266)](https://github.com/Veolinan/RFID_NodeMCU-ESP-8266/commits/master)

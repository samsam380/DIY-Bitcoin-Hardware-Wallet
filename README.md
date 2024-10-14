# DIY Bitcoin Hardware Wallet

# This project allows you to create your own Bitcoin hardware wallet using affordable components like the TTGO T-Display or Lilygo ESP32 boards. The wallet can generate seed phrases, sign Bitcoin transactions offline, and display signed transactions as QR codes for easy scanning and broadcasting.

## Features
- Generate BIP39 seed phrases
- Derive Bitcoin addresses using BIP44
- Sign Bitcoin transactions
- Display signed transactions as QR codes for offline broadcasting

## Hardware Requirements
- TTGO T-Display or Lilygo ESP32 board
- Buttons, camera (optional for QR code scanning)
- Micro-USB cable for flashing firmware

## Setup Guide
1. Install Arduino IDE or PlatformIO.
2. Install the ESP32 board libraries and necessary dependencies.
3. Flash the firmware to the TTGO T-Display.

## How to Use
1. Power on the device and generate a new seed phrase.
2. Sign a Bitcoin transaction using the derived private key.
3. Scan the QR code displayed on the screen to broadcast the signed transaction.

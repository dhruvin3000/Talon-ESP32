# Talon - ESP32 IoT Project

ESP32-based embedded project using PlatformIO.

## Hardware

- **Board:** ESP32 DOIT DevKit v1
- **Platform:** Espressif32
- **Framework:** Arduino

## Setup

\\\ash
# Install PlatformIO CLI
pip install platformio

# Build project
pio run

# Upload to board
pio run --target upload

# Monitor serial output
pio device monitor
\\\

## Project Structure

\\\
Talon/
â”œâ”€â”€ src/              # Source code
â”‚   â””â”€â”€ main.cpp      # Main application
â”œâ”€â”€ include/          # Header files
â”œâ”€â”€ lib/              # Project libraries
â”œâ”€â”€ test/             # Unit tests
â””â”€â”€ platformio.ini    # Configuration
\\\

## Development

- **Developer:** Dhruvin Jayswal (23BT04026)
- **Status:** In development
- **Framework:** Arduino

## PlatformIO Configuration

See \platformio.ini\ for build settings and dependencies.

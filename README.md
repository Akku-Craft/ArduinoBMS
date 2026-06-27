# Akku-Craft Module Firmware

Firmware for the Akku-Craft hardware platform.

This repository contains the source code for the battery management and monitoring firmware.

**Work in Progress**  
This firmware is currently under active development. APIs, features, and structure are subject to change. It is not yet production-ready.

## Scope
This repo focuses on:
- Embedded firmware for the Akku-Craft module
- Battery management logic
- Monitoring, communication, and safety functions
- Build system and configuration

Hardware design files, web interface, and mechanical assets are maintained in separate repositories.

## Old Firmware
The old version is available here:  
[https://github.com/Akku-Craft/ArduinoBMS-old](https://github.com/Akku-Craft/ArduinoBMS-old)

## Requirements
- PlatformIO (recommended) or Arduino IDE
- Compatible toolchain for the target microcontroller
- Git for version control

## Quick Start
1. Clone this repository.
2. Open the project in PlatformIO (or your preferred IDE).
3. Build and flash the firmware to the target hardware.
4. Work from the project root (do not move files out of this directory).

## Repository Structure
```text
src/                  # Main source code
include/              # Header files
lib/                  # External libraries and dependencies
test/                 # Unit and integration tests
platformio.ini        # PlatformIO project configuration
README.md
LICENSE               # Will be added later

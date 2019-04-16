# RDS4Reboot

A (hopefully) better game controller library for current-gen game consoles.

**WARNING**: Work in progress and not ready for general use. API may change at any time.

## Disclaimer

This project is for research purposes only and does not come with any warranty. Use it at your own risk.

## Use cases

- Fightsticks
- Rhythm game controllers
- Accessible controllers
- Creative projects (e.g. beat BloodBorne with bananas, etc.)

## Current status

### Works

- Builds on Teensy LC
- USB Host Shield authenticator with
  - Official controller
  - Hori Mini
- Authentication over USB Host Shield authenticator and Teensy USB transport
- Interrupt IN/OUT reports over Teensy USB transport

### Not (throughly) tested

- Example sketch(es)
- Feedback report handling
- Input report manipulation
- Teensy transport (needs more testing)

### Does not work/WIP

- PluggableUSB transport
- UnoJoy compatibility layer
- Authentication using Guitar Hero Dongle (needs hack)
- Per-project library configuration
- More example sketches

### Planned

- A7105 authenticator
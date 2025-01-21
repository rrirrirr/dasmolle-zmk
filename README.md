# ZMK Config - DASBOB

Custom ZMK firmware configuration for a broken version of [DASBOB](https://github.com/GroooveBob/DASBOB) split keyboard made for Molle. This works with a broken version of the keyboard that you probably don't have and that needs tinkering so, probably, don't try this out if you are not Molle.

## Installation

1. Fork the ZMK config repository
2. Replace the `dasbob.keymap` file with this configuration
3. Update GitHub Actions for your fork
4. Download and flash the firmware

## Building Locally
```bash
west build -b nice_nano_v2 -- -DSHIELD=dasbob_left
west build -b nice_nano_v2 -- -DSHIELD=dasbob_right
```

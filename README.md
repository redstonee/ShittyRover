# Shitty Rover

This is a simple rover that can move around.

## Build

It can be flashed with pyOCD, please install it with the following command:

```bash
pip3 install pyocd
```

Then you're supposed to install the STM32G4xx pack with the following command:

```bash
pyocd pack install stm32g4
```

Finally you can flash the rover with the following command in the `build` directory:

```bash
cmake --build . --target BuildAndFlash
```

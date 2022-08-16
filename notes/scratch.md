# Circuit Measurements
- Facing Pot, pin 1 is left-most, 2 wiper, 3 is right-most

## Horipad Mini 64 - PCB Ver 1.0

Based on the Out-of-Circuit measurements of the X and Y-axis pots, the calculated potentiometer values for the Ver 1.0 Hori PCB are:
- R_13 = ~10kOhms
- R12 = ~5kOhms
- R13 = ~5kOhms

This is virtually the same as the part used in my N64 Joystick Rev -. The only difference is probably that the Hori Ver 1.0 PCB pots have much greater contact resistance. It's also possible that they are non-linear pots and the N64 Joystick Rev - uses linear pots.

### In-Circuit Measurements (w/ ribbon connected to mainboard)
**Stick Centered**
- Rx_13 = 1.613kOhms
- Rx_12 = 2.787kOhms
- Rx_23 = 2.729kOhms
- Ry_13 = 836 Ohms
- Ry_12 = 2.557kOhms
- Ry_23 = 2.555kOhms

### Out-of-Circuit Measurements (w/ ribbon disconnected to mainboard)
**Stick Centered**
- Rx_13 = 4.48kOhms
- Rx_12 = 3.591kOhms
- Rx_23 = 3.689kOhms
- Ry_13 = 4.47kOhms
- Ry_12 = 3.487kOhms
- Ry_23 = 3.459kOhms

## N64 Joystick Rev - (My Design w/ no Added Resistors)

### Out-of-Circuit Measurements
**Stick Centered**
- Rx_13 = 4.93kOhms
- Rx_12 = 3.682kOhms
- Rx_23 = 3.749kOhms
- Ry_13 = 4.92kOhms
- Ry_12 = 3.671kOhms
- Ry_23 = 3.718kOhms

### Individual Potentiometer Measurements (Each axis' pot removed from circuit)
**Stick Centered**
- Rx_13 = 9.88kOhms
- Rx_12 = 4.89kOhms
- Rx_23 = 5.01kOhms
- Ry_13 = 9.81kOhms
- Ry_12 = 4.86kOhms
- Ry_23 = 4.95kOhms

# 4 Resistor Bias Testing



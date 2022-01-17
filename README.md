# Nema 14/17 Toolboard for EVA

Breakout board for EVA to mount to the back of a Nema 17 or name 17 motor. (31mm hole spacing or 43.8mm diagonally).

All signals and power are routed over 2 20p ribbon cables.
For the heater, 5 parallel wires are used to provide enough current. For part fan power, 2 parallel wires are used.

The same board is mounted at the hotend and near the main board.
On the main board side, most components are not mounted, only the connectors.
On the hotend side, all components are mounted except the terminal block in the middle.

## Features
- Everything wired through 2 ribbon cables.
- Spring terminal blocks for: heater, part fan, tool fan, probe, neopixel, aux 1-3
- ADXL345 on board
- Chamber temp PT1000 on board
- Neopixel LED on board and daisy chained to output terminal block
- 3 unused AUX signals

## Jumpers
- On the hotend side, connect 1 of the solder jumpers to select the voltage for the probe
- For correct neopixel routing, connect the hotend solder jumpers on the hotend side and the board solder jumpers on the main board side.


## License
Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
# corexy_klipper
Klipper config files for a corexy 3d printer

See `skr-pico-pinout.png` for board schematics with IO pins labeled. This will help with picking the right plugs/headers for heach element.
The pins in the `printer.cfg` file are consistent with the SKR Pico V1.0 as of 01/01/2025

### Note
When using sensorless homing (as in this `printer.cfg`) You will need to set `stealthchop_threshold` to zero or comment/remove it alltogether.


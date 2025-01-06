# corexy_klipper
Klipper config files for a corexy 3d printer

See `skr-pico-pinout.png` for board schematics with IO pins labeled. This will help with picking the right plugs/headers for heach element.
The pins in the `printer.cfg` file are consistent with the SKR Pico V1.0 as of 01/01/2025

### Note
When using sensorless homing (as in this `printer.cfg`) You will need to set `stealthchop_threshold` to zero or comment/remove it alltogether.

### Voron M4 Pressure Advance Settings
This lines come from the Voron M4 docs.
```
[extruder]
pressure_advance: 0.05
##	Default is 0.040, leave stock
pressure_advance_smooth_time: 0.040
max_extrude_cross_section: 50
max_extrude_only_distance: 200
```
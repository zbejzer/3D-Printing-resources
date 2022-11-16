# Temperature calibration
Two towers with 10mm floors and 0.4mm base, with 10 and 5 levels.

## Klipper commands
Commands that can significantly speedup calibration process. More info [here](https://www.klipper3d.org/G-Codes.html#tuning_tower).

### Extruder temperature
```
TUNING_TOWER COMMAND="SET_HEATER_TEMPERATURE HEATER=extruder" PARAMETER=TARGET START=190 STEP_DELTA=5 STEP_HEIGHT=10 SKIP=0.4
```
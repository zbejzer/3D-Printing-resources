# Retraction calibration
Two towers with 5mm floors and 0.4mm base, with 10 and 5 levels.


## Klipper commands
Commands that can significantly speedup calibration process. More info [here](https://www.klipper3d.org/G-Codes.html#tuning_tower).
### Retraction length
```
TUNING_TOWER COMMAND="SET_RETRACTION" PARAMETER=RETRACT_LENGTH START=0 STEP_DELTA=0.1 STEP_HEIGHT=5 SKIP=0.4
```
### Retraction speed
```
TUNING_TOWER COMMAND="SET_RETRACTION" PARAMETER=RETRACT_SPEED START=10 STEP_DELTA=10 STEP_HEIGHT=5 SKIP=0.4
```

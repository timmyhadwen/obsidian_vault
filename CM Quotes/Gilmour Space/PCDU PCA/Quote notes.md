6 boards hand placed by Mihaela
- Fine pitched so will need to program a stencil printer to print the boards before hand placing

X Ray each board
## Timings
### Stencil Programming/Printing
60 mins
### Hand Place
```math
SMT_PARTS = 87
TH_PARTS = 3
TH_PINS = 42

S_PER_PIN = 10
S_PER_SMT = 30
S_OVEN = 600

DOLLARS_PER_HOUR = 150

TOTAL_TIME = S_PER_PIN*TH_PINS + S_PER_SMT*SMT_PARTS + S_OVEN
TOTAL_TIME_HR = TOTAL_TIME/60

COST = TOTAL_TIME_HR*DOLLARS_PER_HOUR
```
### X-Ray
```math
SETUP_TIME = 45*60

INSP_PER_BOARD_S = 240

COST = SETUP_TIME * *
```

## Costings
### Tooling
- PCB = US$36.4 = $60 AU
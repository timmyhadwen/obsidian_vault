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
PARTS_COST_W_MARGIN = 1807.37

S_PER_PIN = 10
S_PER_SMT = 30
S_OVEN = 5*60

DOLLARS_PER_HOUR = 130

TOTAL_TIME = S_PER_PIN*TH_PINS + S_PER_SMT*SMT_PARTS + S_OVEN
TOTAL_TIME_HR = TOTAL_TIME/60

COST = TOTAL_TIME_HR*DOLLARS_PER_HOUR
COST_PER_UNIT = COST/6 + PARTS_COST_W_MARGIN

# IPC 610 Inspection
# - Critical inspection including independant inspection of all parts

S_PER_BOARD = 60*5 * 2
IPC_COST = (S_PER_BOARD/60)*DOLLARS_PER_HOUR

COST_PER_UNIT_IPC = COST_PER_UNIT + IPC_COST
```

### X-Ray
```math
SETUP_TIME = 45

INSP_PER_BOARD_M = 6

HRS = (SETUP_TIME + INSP_PER_BOARD_M*6)/60
COST = HRS*130
```
## Costings
### Tooling
- PCB = US$36.4 = $60 AU
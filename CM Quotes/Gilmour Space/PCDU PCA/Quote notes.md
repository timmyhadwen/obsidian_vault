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

PARTS_COST_W_MARGIN = 2202.61
STENCIL_SETUP_TIME_M = 45*2
STENCIL_SETUP_TIME_S = STENCIL_SETUP_TIME_M*60

S_PER_THA = 5
S_PER_PIN = 15
S_PER_SMT = 30

S_OVEN = 2*60

DOLLARS_PER_HOUR = 120

TOTAL_TIME_THA = S_PER_PIN*TH_PINS + S_PER_THA*TH_PARTS
TOTAL_TIME_SMT = S_PER_SMT*SMT_PARTS
TOTAL_TIME_S = STENCIL_SETUP_TIME_S + TOTAL_TIME_THA + TOTAL_TIME_SMT + S_OVEN
TOTAL_TIME_HR = TOTAL_TIME_S/60/60

# COST = TOTAL_TIME_HR*DOLLARS_PER_HOUR
COST_PER_UNIT = TOTAL_TIME_HR*DOLLARS_PER_HOUR + PARTS_COST_W_MARGIN

# IPC 610 Inspection
# - Critical inspection including independant inspection of all parts
S_PER_BOARD = 60*3* 2
IPC_COST = (S_PER_BOARD/60) * DOLLARS_PER_HOUR

COST_PER_UNIT_IPC = COST_PER_UNIT + IPC_COST
```
### X-Ray
```math
SETUP_TIME = 60

INSP_PER_BOARD_M = 6

HRS = (SETUP_TIME + INSP_PER_BOARD_M*6)/60
COST = HRS*130
```
## Costings
### Tooling
- PCB = US $726.66 = AU $1,115.07
![[Pasted image 20251021113616.png]]
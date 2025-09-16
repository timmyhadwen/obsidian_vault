```math
CS_10 = 195.51 # 10 QTY
CS_50 = 132.21 # 50 QTY

nre_base = 8050
stencil = 500
pcb_tooling = 300
nre_total = nre_base + stencil + pcb_tooling

# Option 1 - Amortised over 10 units
nre = 2000
unit_price = CS_10 + (nre_total - nre)/10
total = nre + unit_price*10

# Option 2a - Not Amortised
nre = nre_total
unit_price = CS_10 + (nre_total - nre)/10
total = nre + unit_price*10

# Option 2b - Full Amortised
nre = 0
unit_price = CS_10 + (nre_total - nre)/10
total = nre + unit_price*10

# Option 3 - Amortised over 60 units
nre = 3800
nre_rem = nre_base - nre
nre_perunit = nre_rem / 60
unit_price_10 = nre_perunit + CS_10
unit_price_50 = nre_perunit + CS_50

# Option 3 - $2k5 Fixed. No Amortise.
nre = 2000
nre_rem = nre_base - nre
nre_perunit = nre_rem / 60
unit_price_10 = CS_10
unit_price_50 = CS_50

line_price_10 = unit_price_10 * 10 # 10x units pilot
line_price_50 = unit_price_50 * 50 # 50x units serial
```

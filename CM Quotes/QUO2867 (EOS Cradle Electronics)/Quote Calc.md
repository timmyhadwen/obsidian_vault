```math
# Variables
CS = 2009.69 # 5 QTY
nre_h = 71*230
nre_l = 57*230
nre_base = (nre_h + nre_l)/2
stencil = 1000
pcb_tooling = 300
nre_total = nre_base + stencil + pcb_tooling

# Option 1 - Amortised over 5 units
qty = 5
nre = 4500
nre_rem = nre_total - nre
nre_perunit = nre_rem / qty
unit_price = CS + nre_perunit
total = nre + unit_price*qty

# Option 2 - Not Amortised
qty = 5
nre = nre_total
nre_rem = nre_total - nre
nre_perunit = nre_rem / qty
unit_price = CS + nre_perunit
total = nre + unit_price*qty

# Option 3 - Amortised over 70 units
qty = 70
nre = 4500
nre_rem = nre_total - nre
nre_perunit = nre_rem / qty
unit_price = CS + nre_perunit
total = nre + unit_price*qty
```


Ask for golden unit when functional testing is required.
![[Pasted image 20250915161301.png]]
![[Pasted image 20250915161339.png]]
```math
# Variables
CS_5 = 2342.19 # 5 QTY
CS_65 = 1492.09 # 65 QTY
nre_h = 69*230
nre_l = 88*230
nre_base = (nre_h + nre_l)/2
stencil = 1000
pcb_tooling = 300
nre_total = nre_base + stencil + pcb_tooling

# Option 1 - Amortised over 5 units
qty = 5
nre = 4500
nre_rem = nre_total - nre
nre_perunit = nre_rem / qty
unit_price = CS_5 + nre_perunit
total = nre + unit_price*qty

# Option 2 - Not Amortised
qty = 5
nre = nre_total
nre_rem = nre_total - nre
nre_perunit = nre_rem / qty
unit_price = CS_5 + nre_perunit
total = nre + unit_price*qty

# Option 3 - Amortised over 70 units
qty = 70
nre = 4500
nre_rem = nre_total - nre
nre_perunit = nre_rem / qty
unit_price_5 = CS_5 + nre_perunit
unit_price_65 = CS_65 + nre_perunit

# Quote Option 3
nre
ext_price_5 = unit_price_5*5
ext_price_65 = unit_price_65*65
total = nre + ext_price_5 + ext_price_65
```

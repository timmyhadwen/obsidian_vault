```math
CS = 2009.69 # 5 QTY
nre_base = 17000
stencil = 1000
pcb_tooling = 300
nre_total = nre_base + stencil + pcb_tooling

# Option 1 - Amortised over 5 units
qty = 5
nre = 4500
unit_price = CS + (nre_total - nre)/qty
total = nre + unit_price*qty

# Option 2 - Not Amortised
qty = 5
nre = nre_total
unit_price = CS + (nre_total - nre)/qty
total = nre + unit_price*qty

# Option 3 - Amortised over 70 units
qty = 70
nre = 4500
unit_price = CS + (nre_total - nre)/qty
total = nre + unit_price*qty
```

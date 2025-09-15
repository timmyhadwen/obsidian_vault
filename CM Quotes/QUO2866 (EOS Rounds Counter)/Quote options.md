```math
CS = 195.51 # 10 QTY
nre_base = 8050
stencil = 500
pcb_tooling = 300
nre_total = nre_base + stencil + pcb_tooling

# Option 1 - Amortised over 10 units
nre = 3800
unit_price = CS + (nre_total - nre)/10

# Option 2 - Not Amortised
nre = nre_total
unit_price = CS + (nre_total - nre)/10

# Option 3 - Amortised over 50 units
nre = 3800
unit_price = CS + (nre_total - nre)/50
```

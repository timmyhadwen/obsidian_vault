```math
HEADSET_COST = 80
SWITCH = 4
AUDIO_INTERFACE = 8

MINUTES_PER = 15
PRODUCTION_HOURLY = 120

TOTAL_COST = HEADSET_COST + SWITCH + AUDIO_INTERFACE + MINUTES_PER*PRODUCTION_HOURLY/60
MARGIN = 1.2
TOTAL_COST_W_MARGIN = TOTAL_COST * MARGIN

TARGET_COST = 179.99
MARGIN = TARGET_COST - TOTAL_COST_W_MARGIN

NRE = 4500
```

Costs:
- AU$80 headset - https://koss.com/products/sb45-usb
- AU$4 switch - https://www.digikey.com.au/en/products/detail/e-switch/100SP2T1B1M2QEH/1803215?gclsrc=aw.ds&gad_source=1&gad_campaignid=22258692864&gclid=EAIaIQobChMInLfxw8v4kAMVSyJ7Bx30tRGtEAQYASABEgJffvD_BwE
- AU$4.95 audio interface - https://www.digikey.com.au/en/products/detail/adafruit-industries-llc/1475/7244940?gclsrc=aw.ds&gad_source=1&gad_campaignid=22258692864&gclid=EAIaIQobChMIuPmE0Mv4kAMVWFwPAh2buQpPEAQYBiABEgLKFfD_BwE
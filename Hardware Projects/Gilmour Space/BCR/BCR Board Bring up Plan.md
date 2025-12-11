## Power supplies
1. Apply 28V to J2 MPPT_BUS using test cable
2. Measure voltage at TP3 should be appx 28V
3. Measure voltage over C130, should be appx 28V
	1. This is the system voltage
4. Measure voltage at TP4, should be 3V8
5. Measure voltage at TP5, should be 3V3
	1. Watchdog controls core enable
6. Measure voltage at TP7 (may need enable pin)
7. Measure voltage at TP8 (may need enable pin)
8. Measure voltage at TP9 (may need enable pin)

## MPPT
1. Inject 28V/0.5A into PV1_A/B
	1. Monitor MPPT_OUT at TP1
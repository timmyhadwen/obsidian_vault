Discharge battery
echo 0 | sudo tee /sys/class/power_supply/battery_gauge/charge_now
Full charge
cat /sys/class/power_supply/battery_gauge/charge_now echo {VALUE} | sudo tee /sys/class/power_supply/battery_gauge/charge_full
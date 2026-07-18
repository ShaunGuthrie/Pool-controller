# Pool Controller TODO

## High Priority
- [ ] dose_arm_relay pin 6 wiring
- [ ] b_off LVGL button highlights
- [ ] service mode still doesnt always set.  review scripts

## Medium Priority  
- [ ] set dosing previous pump status  possible set rev pump state that reverts to desired after things are done running.  use increment to add to a global so unless global is 0 it doesnt revert/
- [ ] Voltage monitoring (12V/5V/3.3V) hardware wiring
- [ ] DHT22 replacement sensor sht312
- [ ] Water level sensor setup and calibration
- [ ] Salt PPM multiplier verify (×50 vs ×100)
- [ ] fix super chlor remaining, verify it goes to 0 when not in super chlor

## Hardware Pending
- [ ] Install pH and ORP probes (Atlas Surveyor)
- [ ] Install filter pressure sensor
- [ ] Contactors for 2-speed pump
- [ ] Century VS pump (future)
- [ ] Auto fill/drain valve (future)

## Future Features
- [ ] ORP-based chlorinator lockout
- [ ] VS pump RPM control + LVGL UI
- [ ] Scheduled 4AM reboot (if needed)
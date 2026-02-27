## Nixie Tube Clock ##

A digital clock and thermometer using ATMega328-P for controll, DS3231 RTC for precise timing and BMP280 for pressure and temperature.
For display it uses the following tubes (from USSR):
- 4x IN-14 for digits
- 1x IN-19 for units (hard to obtain; not strictly necessary, but makes the display clearer)

Takes 12V DC as input. Requires external step-up HV 170V converter.

IMPORTANT: The L7805 power regulator heats up quite a lot. A 5V buck converter would probably be a better choise.

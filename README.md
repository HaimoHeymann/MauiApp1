Decimal point on numeric keyboard not working since Net8.0

**Since the update to Net8.0**: Cannot type the decimal point into an _Entry_ control using the softkeyboard with NUMERIC layout.
This happen only on a real Android device like Android Phone (API 33) oder Android Tablet (API 30). The emulator works correct.
iOS devices are also do fine

1. create new MAUIApp
2. add entry with KEYBOARD.NUMERIC
3. run and try to enter a decimal point

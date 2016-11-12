# RGBShadesHoliday
Special RGB Shades code with selectable Christmas and New Years patterns

HOW TO SWITCH MODES

1. Turn off RGB Shades
2. Hold down button(s) to select modes as below:
      * Button 1: New Years
      * Button 2: Christmas
      * Buttons 1 and 2: Normal mode
3. While holding down your selected button(s), turn the RGB Shades on
4. RGB Shades will be in the selected mode
5. This mode will be saved in EEPROM so you only need to do it once per mode change


Use Version 3.0 or later https://github.com/FastLED/FastLED
ZIP file https://github.com/FastLED/FastLED/archive/master.zip

Use Arduino IDE 1.0 or later

If your RGB Shades were purchased before July 2015:
     This version has the standard Arduino bootloader. R9 and R10 near the control buttons will be present.
     Select the “Arduino Pro or Pro Mini” option.
     Then, go back into the Tools menu and find the Processor option and select “ATmega328 (5V, 16MHz)”.

If your RGB Shades were purchased after July 2015:
     This version has the Optiboot bootloader. R9 and 10 near the control buttons will be missing.
     Select the “Arduino Mini” option.
     Then, go back into the Tools menu and find the Processor option and select “ATmega328”.

[Press] the SW1 button to cycle through available effects

[Press and hold] the SW1 button (one second) to switch between auto and manual mode
     * Auto Mode (one blue blink): Effects automatically cycle over time
     * Manual Mode (two red blinks): Effects must be selected manually with SW1 button

[Press] the SW2 button to cycle through available brightness levels

[Press and hold] the SW2 button (one second) to reset brightness to startup value

Brightness, selected effect, and auto-cycle are saved in EEPROM after a delay.

The RGB Shades will automatically start up with the last-selected settings

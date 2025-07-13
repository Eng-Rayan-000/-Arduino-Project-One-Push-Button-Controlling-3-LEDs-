# Arduino Project One Push Button Controlling 3 LEDs
   Arduino Project: One Push-Button Controlling 3 LEDs (Toggle Mode)
    Description
This Arduino sketch allows a single push-button to control three LEDs using a toggle mechanism:

Press the button once → all LEDs turn ON.

Press it again → all LEDs turn OFF.

Repeats on every press.

 How It Works
Uses INPUT_PULLUP for button input (active LOW).

Detects a state change from HIGH to LOW (button press).

Toggles the ledsState boolean to switch LED states.

Adds a short delay(100) for debouncing.


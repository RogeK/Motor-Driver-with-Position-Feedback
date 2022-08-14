**Status LEDs**

There are 3 status LEDs, one is positioned near the jack and turns on to indicate that the PiHat is connected to the mains. The second and third LEDs are connected on the output pins Q1 and Q2 of the motor driver through a hold up circuit. These two LEDS turn on to indicate that the motor is running. Since the output of the motor driver is a PWM signal, the LEDS were found to be increasing and decreasing in brightness depending on the duty cycle. To prevent this, a hold up circuit was placed between the led and the motor driver.

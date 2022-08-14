1. The Motor Position Feedback Subsystem is made up of the incremental encoder, the motor driver L293D and the Pi  

2. The motor driver L293D acts as our amplifier. It sinks 250mA from the Power Supply and amplifies it to 2A  

3. The incremental encoder will be connected to the shaft of the DC motor M1N10FB11G.It will however be controlled by the board through its pins.  

4. The encoder has 6 pins that will be connected to the PiHat through screw terminals instead of header pins which may not work well in a dusty environment.  

5. The pins of the encoder are as follows:

| PIN | Description |
| ------ | ------ |
| Q1 | Supplies current into/out of the motor from the motor driver. Receives instructions from the Pi through the motor driver. The status LED 2 is connected to this pin to indicate when the motor is running |
| Q2 | Supplies current into/out of the motor from the motor driver. Receives instructions from the Pi through the motor driver. The status LED 3 is connected to this pin to indicate when the motor is running |
| Vcc | Powers the encoder. |
| GND | Ground Pin |
| Digital Pin 1 | Sends feedback to the Pi regarding the motors position and direction. |
| Digital Pin 2 | Sends feedback to the Pi regarding the motors position and direction. |

6. Pins Q1 and Q2 from the encoder will be connected to the output of the motor driver L293D which will serve to amplify the low current from the voltage regulator to a high enough current that can drive the motor  

7. The L293D was also chosen because of its high-Noise-Immunity Inputs protecting the subsystem against noise that may come from the power supply and from the inrush current it may experience when the motor turns on  

8. The pins of the L293D are as follows:

| PIN | Description |
| ------ | ------ |
| 1 | Enable pi. When this pin is powered, it enables pins 1 and 2. |
| 2 | Receives input from the Pi through GPIO4 of the Pi which is accessible through the header pins. |  
| 3 | This is the output pin of pin 2. Offers path for bidirectional current to and from the motor. |
| 6 | This is the output to pin 3. Offers path for bidirectional current to and from the motor. |
| 7 | Receives input from the Pi through GPIO3 of the Pi which is accessible through the header pins. |

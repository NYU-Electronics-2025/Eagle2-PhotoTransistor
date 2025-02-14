# Eagle2-PhotoTransistor

For this assignment, you'll make a circuit that can detect when you wave your finger over it. 

We'll use a matched LED/phototransistor pair in a single part. When you put a current through the LED, it shines infrared light up. The phototransistor detects light reflected back. 

The phototransistor acts like a regular transistor, except that I_base is supplied by light (there isn't a separate pad to hook up the base, so there are only two terminals). We'll send the amplified current (I_e = beta I_b) through a resistor R_E to ground to generate a voltage. This voltage will be used to switch on a second NPN transistor that will activate a visible LED. We'll control the sensitivity by making R_E a variable resistor. 

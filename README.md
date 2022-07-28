# 555-Timer-50-Duty-Cycle-Sponsored-by-JLCPCB

Thank you JLCPCB for sponsoring this project. Please order your PCB at https://jlcpcb.com/RAT

Hardware components
	
JLCPCB Customized PCB ×	1	

NE555 Timer through hole ×	1	

IC socket 8 pins 2.54mm through hole ×	1	

Male Header 40 Position 1 Row (0.1") ×	1	

Capacitor 10 nF ×	2	

0.25W 1000 Ohm Resistor ×	2	

1N4007 – High Voltage, High Current Rated Diode ×	2

Hand tools and fabrication machines

Soldering iron (generic)
	
Solder Wire, Lead Free

This project is about 555 Timer which produces 50% duty cycle. Use a ceramic capacitor for C2.

I would also like to thank the online community for sharing the schematic to build the circuit.

Why do we want a 555 Timer instead of a microcontroller signal output?

A 555 Timer can provide up to about 14V output peak to peak signal. Whereas, a microcontroller usually can provide up to 5V peak to peak signal.

Please use a constant input voltage of between 5V and 15V for the NE555 Timer.

For example, using the Frequency meter Arduino code, with R1 = R2 = 10k Ohms, C1 = 33 nF, frequency = 1500 Hz.

With the help of an Arduino, you can use the Frequency meter .ino code to find out the frequency and duty cycle of a 555 Timer.

![image](https://user-images.githubusercontent.com/85741357/181506525-2f506304-d36a-499c-9afe-0cddcddd0865.png)

R1 = R2 = 300 Ohms, C1 = 33 nF, f = 1500 Hz

I have yet to figure out the formula for calculating the frequency of the 555 Timer for this setup. Do let me know if you have the answer.
One application of 50% duty cycle is the use as a music frequency generator. You can set your PCB to a specific frequency and connect it to a speaker and a push button.

Tips: JLCPCB offers cheaper price for small PCBs of 10cm by 10cm. You can panelize your PCBs to less than or equal to the dimension.

Hope you enjoy this project. Once again, I would like to thank JLCPCB for sponsoring this project, and please order your PCBs at https://jlcpcb.com/RAT

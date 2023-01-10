# Square-Wave-Generator-

*Making a Square Wave*

_Compenents :-_

• NE 555
• IC 741
• 1 Mega Om Variable Resistor 
• 100 k Resistors × 2
• 12 V Battery , 6 V Batteries × 2
• 1 uF Electrolytic  Capacitor 
• 1 nF Non Electrolytic Capacitor 

NE 555 is used to make the Pulse
T On = ln 2 × ( R1  + R2) × C1 
T Off = ln 2 ×  R2  × C1

For a Square Wave,

R1 = 0 Om

T On = T Off = ln 2 × R2 × C1

T = 2×  ln 2 ×R2 × C1

T = 2 × 0.693 × 10^6 × 10^-6 × x/100

T = 1.386  × x/ 100

0 <= x <= 100

So, the Frequenzy of the Wave can be changed by the wiper of the Variable Resistor...

V Out will be 12 V and 0 V with a Time Period of 1.386 x / 100 s...

So,
The Op Amp is at the Open Loop Condition...

Now,
V Out = A ( V+  -  V-)

A = 10^5 for an Op Amp...

Because of that,
When,
V+  >  V-
V Out = +Vs = +6 V

V-   >  V+ 
V Out = -Vs  = -6 V

The Amplitude of the Square wave can be changed by changing the Supply Voltages...


*Arjun ( Isuru ) 🍁✨*

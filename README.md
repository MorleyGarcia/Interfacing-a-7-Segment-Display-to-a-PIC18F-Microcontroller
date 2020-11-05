# Interfacing-a-7-Segment-Display-to-a-PIC18F-Microcontroller
Program Used: MPLAB IDE
•Built a circuit that would take four switches as inputs into a PIC18F and then the outputs go into a 7 Segment Display
•Using Assembly language I programmed the PIC18F to interpret the inputs into hex values depending if the switches were down or up and stored them in Port A to represent our input
•Next I converted the hex values into BCD format and assigned them to Port B to represent the output
•Example: A 24 hex value input yields a 2 on the display, A 10 hex value input yields a 9 on the display

# Requirements
## Components
* ATmega328 Microcontroller
* 3 resistors
* 330 Ohm Resistos-2
* 10 KOhm Resistor-1
* Reset Button
* Input Button
* Ground
* 2 LED's
# DDRx  
Data Direction Register configures data direction of the port(Input/Output). The instruction “ DDRB |= (1<<DDB2)”  makes corresponding port pin as output.
# PORTx 
Port register is for assigning appropriate values for the port pins.
Writing to PORTx.n will immediately change state of the port pins according to given value. “PORTB |=(1<<PORTB2)” will generate a high signal at PB2. And “PORTB&=~(1<<PORTB3)” is for generating a low signal at PB3.

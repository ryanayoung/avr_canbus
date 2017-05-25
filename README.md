# avr_canbus

 This project communicates between two microcontrollers using the canbus protocol and 
two canbus breakout boards. From a serial terminal on a pc it can receive a byte over UART, 
then it sends that bite over SPI to the MCP2515 canbus transceiver, which in turn sends it to the 
other canbus breakout board. The second microcontroller then reads the data over SPI and 
transmits it over UART to another serial terminal. This process works exactly the same in the 
opposite direction. 
These are example programs to be run on a micro:bit to be used with the create binary models webpage
Each of these models send a stream of 1s and 0s down the serial port when connected to a computer 
When the webpage makes predictions and returns the name of the predicts, there programs will print the name on the LED display
They will then send out a radio signal with the name of the record aswell
you can drag and drop these files into the micro:bit microsoft makecode editor to look at the code 

Binary Button
sends 1s when the B button is being pressed, sends 0 the rest of the time 

Binary magnet
sends 1s when the micro:bit senses a strong enough magnetic force, sends 0s the rest of the time

Binary tilt
sends 0s when the micro:bit is positioned with the face up, sends 1s the rest of the time

The fourth file is the radio reciever file. This can be downloaded on to a second micro:bit that will recieve the radio signals from the first micro:bit when it is recieving predictions from the model
these predictions will also be displayed on this micro:bit

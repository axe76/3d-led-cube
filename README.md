# Sound-Signal-responsive-3d-led-cube
The code is a MATLAB code that allows a 4x4 LED Matrix to respond to the pitch of sound signals and Light Up the appropriate number of Rows, Thus producing a "dancing" in response to sound signals like those from songs. 
Here, the Arduino Package for MATLAB has been imported.
The code controls 4 ports of an Arduino to control the 4 layers of a 4x4 LED Cube.
The layers of the cube are the anodes of the LED cube while the columns are cathodes.
The cathodes (columns) are given a low potential (LOW signal) from another arduino and when the appropriate layer gets a HIGH signal from the MATLAB controlled Arduino, the LEDs are forward biased and they turn on.
NOTE: The Grounds of the 2 Arduinos must me made common.

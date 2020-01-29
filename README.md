# Arduino-Delay
This delay effect was built along as part of a project for a Audio Systems, having to build and input and filtering stage as well as the output stage electronically. The main modification of the code is at the bottom of the project as the rest was template, built to read in a signal, and able to use the arduinos digital pins to output the signal through the DAC built. 

The code works follwoing a circular buffer, allowing the signal to be delayed 4 samples ahead. Specified in the brief was to design a feedback comb filter, this meant that the output had to feedback into the input of the buffer.

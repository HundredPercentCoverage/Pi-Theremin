# Pi-Theremin
Using Python and PureData to make an ultrasonic theremin.

Based on the ultrasonic theremin code found in MagPi Issue 58 (June 2017). I decided to use PD instead of Sonic Pi. I used a float to act as frequency instead of MIDI note numbers in the python script to help smooth the tone.

Requires an HC-SR04 ultrasonic distance sensor and the pythonosc library (simply type sudo pip3 install python-osc into the terminal).

# Digital-Video-Glitcher
Ultrasonic Ardiuno Digitial Video Glitcher a la Karl Klomp

Based on Karl Klomp video glitcher design, with digital potentiameter instead of manual, and an ultrasonic proximity sensor instead of the audio mics in the video.

Inspired by @getcircuitbent  

https://www.youtube.com/watch?v=zg-kOUHmbnk&t=1s

Using an Arduino R3 microprocessor. Currently in breadboard stage with two video inputs and one video output that glitches between the two video inputs as the proximity signal changes. 

X9C102 digital pot to crossfade between two video signals.
HC-SR04 Ultrasonic sensor mapped to send proximity distance within 0-100 range value of digipot. <50 towards channel 1, >50 towards channel 2 with a gradual transistion between. 

Based on the library Arduino-X9C by Phil Bowles (https://github.com/philbowles/Arduino-X9C)

pot.value is set for true for testing purposes but will be set to false when running. 

10k resistors between INC/ground and CS/ground. 
.1uF capacitor between VCC and VSS. 

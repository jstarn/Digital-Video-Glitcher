# Digital-Video-Glitcher
Ultrasonic Ardiuno Digitial Video Glitcher a la Karl Klomp

Based on Karl Klomp video glitcher design, with digital potentiameter instead of manual, and a proximity sensor instead of the audio mics in the video.

Inspired by @getcircuitbent  

https://www.youtube.com/watch?v=zg-kOUHmbnk&t=1s

Using an Arduino Uno R3 microprocessor.

MCP4101 digital pot to crossfade between two video signals.
VL503X Ultrasonic sensor mapped to send proximity distance within 0-100 range value of digipot. <50 towards channel 1, >50 towards channel 2 with a gradual transistion between. 

.1uF capacitor between VCC and VSS. 

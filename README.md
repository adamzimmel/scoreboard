# scoreboard
Baby Steps of the Project
1. Turn on LEDs
2. Turn on Relay with RPi
3. Count Down Timer with RPi
4. Set up a 8-bit shift register to control Relays
5. Set Scores, Innings, Balls, Strikes and Outs
6. Set Time Of Day
https://www.e-tinkers.com/2018/04/how-to-control-raspberry-pi-gpio-via-http-web-server/

*Can you make a "captive portal" for the web interface? As soon as the client connects to
scoreboard wifi, it redirects to the captive portal page.

*To control multiple lights with only a few inputs, I think is called Multiplexing.

*8-bit Shift Register 74HC595N
A shift register is a chip you can use to control many outputs (8 here) at the same time while only using a few pins (3 here) of your Arduino.

Some dude who triggered water pumps via the gpio pins. 
He used realays also which is why his wiring diagrams might prove useful. 
https://github.com/brycedewitt/ASMARK2

https://lastminuteengineers.com/74hc595-shift-register-arduino-tutorial/

# Pure-sinewave-inverter
This is a simple affordable pure sine wave 1kVA inverter for a battery back up system.
I used IC 4017 with an IC NE555 oscilator to generate PWM signal which makes the circuit more accurate and the wave form is uniform and does not depend on external adjustments.
I used 10 IRS3250 mosfets to allow the circuit to handle the stated 1000W power.
The transformer can be choosen depending on the required voltage outpt, but it must be a 3p/2s one.
You can notice that I routed the mosfets battery input on both sides, I did this to allow the traces to handle the high current from the battery without rising the price of manufacturing, which is 24USD for the bare board from PCBWAY.
Feel free to try out the cicuit yourself.

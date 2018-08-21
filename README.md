# Arduino Nano based Speedlight Flash duration measurements
This code is adapted and extended from Vela.io version for an Arduino Leonardo. 
(For more details on the original code and hardware setup see http://www.vela.io/posts/how-fast-is-your-flash/)

# Arduino Nano v3 Pins
- Digital Pin 2 :arrow_right: INT0 -> Button
- Digital Pin 6 :arrow_right: AINO -> BPW34 or SFH203 photodiode at ADC multiplexer
- Digital Pin 7 :arrow_right:      -> Mosfet flash trigger
- Analog Pin 0  :arrow_right: ADC0 -> Analog Comparator

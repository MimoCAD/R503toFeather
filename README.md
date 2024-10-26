# Pinout
We start by connecting the Grow r503 (Pro) to the RP2040 Pico W with the following pinout.
![RP2040 Pico W Pinout](https://www.raspberrypi.com/documentation/microcontrollers/images/picow-pinout.svg)

| # | Sensor Wire Color                      | Function |  PIN#  | Pin Name                                      |
| - |                  :---:                 |   :---:  |  :---: |                :---:                          |
| 1 | $${\color{red}RED \space Wire}$$       | Power    |   36   | $${\color{red}3V3(OUT)}$$                     |
| 2 | $${\color{white}WHITE \space Wire}$$   | Ground   |   38   | $${\color{black}GND}$$                        |
| 3 | $${\color{yellow}YELLOW \space Wire}$$ | TX (Out) |   21   | $${\color{purple}UART0 \space RX (GPIO 17)}$$ |
| 4 | $${\color{purple}PURPLE \space Wire}$$ | RX (In)  |   22   | $${\color{purple}UART0 \space TX (GPIO 16)}$$ |
| 5 | $${\color{blue}BLUE \space Wire}$$     | Wakeup   |   24   | $${\color{lightgreen}GPIO 18}$$               |
| 6 | $${\color{white}WHITE \space Wire}$$   | Touch    |   36   | $${\color{red}3V3(OUT)}$$                     |

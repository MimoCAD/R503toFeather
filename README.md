# Pinout

## Adafruit Feather RP2350 HSTX
![Adafruit Feather RP2350 HSTX Pinout](https://raw.githubusercontent.com/adafruit/Adafruit-Feather-RP2350-PCB/refs/heads/main/Adafruit_Feather_RP2350_prettypins.svg)

## Grow R503 Pro
![GROW R503 Pro MX1.0-6P Pinout](https://probots.co.in/pub/media/wysiwyg/GROW_R503_-5.jpg)

## Connections
| # | R503 Pro Wire Color                    | Name   | PIN # | Pin Name               | Notes                            |
| - |                 :---:                  | :---:  | :---: |          :---:         |               :---:              |
| 1 | $${\color{red}RED \space Wire}$$       | Power  |   3V3 | $${\color{red}3V3}$$   | 3.3 Volts (Top Left Of Feather). |
| 2 | $${\color{black}BLACK \space Wire}$$   | GND    |   GRD | $${\color{black}GND}$$ | Ground (Right Under 3.3 Pins).   |
| 3 | $${\color{yellow}YELLOW \space Wire}$$ | TXD    |    01 | $${\color{green}RX}$$  | TX on R503 <> RX on the Feather. |
| 4 | $${\color{green}GREEN \space Wire}$$   | RXD    |    00 | $${\color{yellow}TX}$$ | RX on R503 <> TX on the Feather. |
| 5 | $${\color{blue}BLUE \space Wire}$$     | Wakeup |    02 | $${\color{BLUE}SDA}$$  | Finger Detection (Pulled High).  |
| 6 | $${\color{white}WHITE \space Wire}$$   | Touch  |   3V3 | $${\color{red}3V3}$$   | 3.3 Volts (Top Left Of Feather). |

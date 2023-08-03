# WS2812 / SK6812 Ethernet Controller Custom PCB

Control your addressable LED with custom software like [WLED](https://github.com/Aircoookie/WLED)

[Gerber-Files](https://github.com/klein0r/pcb-ws2812-ethernet-controller/releases)

## Preview

![PCB Preview](https://raw.githubusercontent.com/klein0r/pcb-ws2812-ethernet-controller/master/preview.png)

![PCB Photo](https://raw.githubusercontent.com/klein0r/pcb-ws2812-ethernet-controller/master/previewReal.jpg)

## Components

- WT32-ETH01 ESP32
- C1: Capacitor Radial 3.8mm 1000μF 6.3
- F1: Stelvio Kontek STV PTF/75 + Fuse 5x20mm, 5A (max. 6A)
- J1: PHC 1725672 - MPT 0,5 / 4-2,54
- J2: PHC 1725669 - MPT 0,5 / 3-2,54
- J3: 1x4 2.54mm Male Pin Headers (for flashing - soldering not required)
- J4: 1x2 2.54mm Male Pin Headers (for flashing - jumper)
- U1: WT32-ETH01
- U2: SN74AHCT125DR
- R1: Resistor 0805 330

[Component list (Affiliate-Link)](https://haus-auto.com/p/rei/ListeWS2812Eth)

## GPIO

- GPIO2 = Data line of addressable strip

## License

The MIT License (MIT)

Copyright (c) 2023 Matthias Kleine <info@haus-automatisierung.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

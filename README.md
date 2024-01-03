# Tasmota-HDMI-CEC-Example
Bin with HDMI-CEC enabled With Alexa control
See https://tasmota.github.io/docs/HDMI_CEC/ for more information 

Included is the user_config_override.h used for compilation

<table> <thead> <tr> <th style="text-align: left;" role="columnheader">Wemos D1 Mini</th> <th style="text-align: left;" role="columnheader">Configuration</th> <th style="text-align: left;" role="columnheader">HDMI</th> </tr> </thead> <tbody> <tr> <td style="text-align: left;">GPIO 2</td> <td style="text-align: left;">HDMI CEC</td> <td style="text-align: left;">HDMI Pin 13<br>GPIO 2 on Wemos D1 Mini is connected to a blue Led which is a visual indicator of CEC traffic</td> </tr> <tr> <td style="text-align: left;">GPIO 4</td> <td style="text-align: left;">I2C SDA</td> <td style="text-align: left;">HDMI Pin 16</td> </tr> <tr> <td style="text-align: left;">GPIO 5</td> <td style="text-align: left;">I2C SCL</td> <td style="text-align: left;">HDMI Pin 15</td> </tr> <tr> <td style="text-align: left;">Ground</td> <td style="text-align: left;"></td> <td style="text-align: left;">HDMI Pin 17</td> </tr> <tr> <td style="text-align: left;">+5V</td> <td style="text-align: left;"></td> <td style="text-align: left;">HDMI Pin 18<br>If another device is present on the same HDMI port, it provides +5V with enough power for ESP8266. In such case you don't need an external power (tested with AppleTV).</td> </tr> </tbody> </table>

I uploaded code with Tasmotizer https://github.com/tasmota/tasmotizer and added the wifi credentials that way, but do whatever works for you.

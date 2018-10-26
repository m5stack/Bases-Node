# M5StackModule-Node

**Docs about the Node Module designed by M5Stack**

The Node is a sound box module with 12 RGBLed(SK6812), a codec chip(WM8978), DHT12, IR Transmitter and Receiver(CHQ0038H), two MICs. WM8978 is often used to be applied for Hi-Fi Speaker. You can program it after connected to any series of M5Stack Core through Arduino.

You can creat a Webradio, Bluetooth Speaker, even Intelligent sound box with this module.

*For verifying the hardware, you can burn these [example codes](https://github.com/watson8544/M5StackModule-Node/tree/master/Example) to Node.*

### PinMap

| **Codec Chip(WM8978)**     | **ESP32**  |
| :------------------:  |:------------------:|
| I2C_SDA | GPIO21 |
| I2C_SCL | GPIO22 |
| L_OUT1 | GPIO25 |
| I2S_CLK_24M | GPIO0 |
| I2S_IN | GPIO2 |
| I2S_OUT | GPIO34 |
| I2S_BCK | GPIO5 |
| I2S_WS | GPIO13 |

| **RGBLed(SK6812)**     | **ESP32**  |
| :------------------:  |:------------------:|
| SK6812 | GPIO15 |

| **IR**     | **ESP32**  |
| :------------------:  |:------------------:|
| IR_Receive | GPIO35 |
| IR_Send | GPIO12 |

| **DHT12**     | **ESP32**  |
| :------------------:  |:------------------:|
| I2C_SDA | GPIO21 |
| I2C_SCL | GPIO22 |

 - [Schematic](https://github.com/watson8544/M5StackModule-Node/tree/master/schematic)
 - [Example](https://github.com/watson8544/M5StackModule-Node/tree/master/Example)
 - [Purchase](https://github.com/watson8544/M5StackModule-Node/tree/master/Purchase)

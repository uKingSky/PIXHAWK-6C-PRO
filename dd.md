# Ports Define

Pin 1 starts from the flight controllers "right side" like diagram below​

![](/assets/image.jfif)

#### **Power1 & 2** {#power1-and-2}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VDD5V\_BRICK1 \(in\) | +5V |
| 2\(black\) | VDD5V\_BRICK1 \(in\) | +5V |
| 3\(black\) | CURRENT1 | +3.3V |
| 4\(black\) | VOLTAGE1 | +3.3V |
| 5\(black\) | GND | GND |
| 6\(black\) | GND | GND |

#### **Telem 1 Port** {#telem-1-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VCC | +5V |
| 2\(black\) | UART7\_TX\(out\) | +3.3V |
| 3\(black\) | UART7\_RX\(in\) | +3.3V |
| 4\(black\) | UART7\_CTS\(in\) | +3.3V |
| 5\(black\) | UART7\_RTS\(out\) | +3.3V |
| 6\(black\) | GND | GND |

#### **Telem 2 Port** {#telem-2-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VCC | +5V |
| 2\(black\) | UART5\_TX\(out\) | +3.3V |
| 3\(black\) | UART5\_RX\(in\) | +3.3V |
| 4\(black\) | UART5\_CTS\(in\) | +3.3V |
| 5\(black\) | UART5\_RTS\(out\) | +3.3V |
| 6\(black\) | GND | GND |

#### **Telem 3 Port** {#telem-3-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VCC | +5V |
| 2\(black\) | USART2\_TX\(out\) | +3.3V |
| 3\(black\) | USART2\_RX\(in\) | +3.3V |
| 4\(black\) | NOT CONNECTED\* | - |
| 5\(black\) | NOT CONNECTED\* | - |
| 6\(black\) | GND | GND |

**\* For Pixhawk 6C with SN number**`XXXX 001 XXXXXX`**\(SN can be found on the packaging\), Telem3 port is connected as follow:**

* pin 4 -&gt; I2C4\_SCL \(3.3V\)

* pin 5 -&gt; I2C4\_SDA \(3.3V\)

**Do not connect Non-I2C device \(such as telemetry radio\) to telem3 pin 4 & 5 if you have this version.**

#### **GPS 1 Port** {#gps-1-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VCC | +5V |
| 2 black\) | TX1\(out\) | +3.3V |
| 3\(black\) | RX1\(in\) | +3.3V |
| 4\(black\) | SCL1 | +3.3V |
| 5\(black\) | SDA1 | +3.3V |
| 6\(black\) | SAFETY\_SWITCH | +3.3V |
| 7\(black\) | SAFETY\_SWITCH\_LED | +3.3V |
| 8\(black\) | IO\_VDD\_3V3 | +3.3V |
| 9\(black\) | BUZZER- | 0~5V |
| 10\(black\) | GND | GND |

#### **GPS2 Port** {#gps2-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VCC | +5V |
| 2 black\) | UART8\_TX\(out\) | +3.3V |
| 3\(black\) | UART8\_RX\(in\) | +3.3V |
| 4\(black\) | I2C2\_SCL | +3.3V |
| 5\(black\) | I2C2\_SDA | +3.3V |
| 6\(black\) | GND | GND |

#### **USB Port** {#usb-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VBUS | +5V |
| 2\(black\) | DM | +3.3V |
| 3\(black\) | DP | +3.3V |
| 4\(black\) | GND | GND |

#### **I2C Port** {#i2c-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VCC | +5V |
| 2\(black\) | I2C2\_SCL\* | +3.3V |
| 3\(black\) | I2C2\_SDA\* | +3.3V |
| 4\(black\) | GND | GND |

**\* For Pixhawk 6C with SN number**`XXXX XXX 20221100`**AND prior,\(SN can be found on the packaging\), I2C port is connected as follow:**

* pin 2 -&gt; I2C4\_SCL \(3.3V\)

* pin 3 -&gt; I2C4\_SDA \(3.3V\)

#### **CAN1 & CAN2 Port** {#can1-and-can2-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | VCC | +5V |
| 2\(black\) | CAN1\_H | +3.3V |
| 3\(black\) | CAN1\_L | +3.3V |
| 4\(black\) | GND | GND |

#### **DSM RC Port** \(JST-ZH 1.5mm\) {#dsm-rc-port-jst-zh-1.5mm}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(yellow\) | VDD\_3V3\_SPEKTRUM | +3.3V |
| 2\(black\) | GND | GND |
| 3\(gray\) | DSM/SPEKTRUM IN | +3.3V |

#### **PPM/SBUS RC port** {#ppm-sbus-rc-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(null\) | VDD\_5V\_PPM\_SBUS | +5V |
| 2\(yellow\) | PPM&SBUS\_IN | +3.3V |
| 3\(null\) | RSSI\_IN | +3.3V |
| 4\(red\) | \(NOT CONNECTED\) | -- |
| 5\(black\) | GND | GND |

#### **SBus Out Port** {#sbus-out-port}

| **Pin** | **Signal** | **Voltage** |
| :--- | :--- | :--- |
| 1\(red\) | \(NOT CONNECTED\) | -- |
| 2\(yellow\) | SBUS\_OUT | +3.3V |
| 3\(black\) | GND | GND |

#### **FMU PWM Out** {#fmu-pwm-out}

| Pin | Signal | Voltage |
| :--- | :--- | :--- |
| 1 \(Red\) | VDD\_Servo |  |
| 2 \(Black\) | FMU\_CH1 | +3.3V |
| 3 \(Black\) | FMU\_CH2 | +3.3V |
| 4 \(Black\) | FMU\_CH3 | +3.3V |
| 5 \(Black\) | FMU\_CH4 | +3.3V |
| 6 \(Black\) | FMU\_CH5 | +3.3V |
| 7 \(Black\) | FMU\_CH6 | +3.3V |
| 8 \(Black\) | FMU\_CH7 | +3.3V |
| 9 \(Black\) | FMU\_CH8 | +3.3V |
| 10\(Black\) | GND | GND |

#### **I/O PWM Out** {#i-o-pwm-out}

| Pin | Signal | Voltage |
| :--- | :--- | :--- |
| 1 \(Red\) | VDD\_Servo |  |
| 2 \(Black\) | IO\_CH1 | +3.3V |
| 3 \(Black\) | IO\_CH2 | +3.3V |
| 4 \(Black\) | IO\_CH3 | +3.3V |
| 5 \(Black\) | IO\_CH4 | +3.3V |
| 6 \(Black\) | IO\_CH5 | +3.3V |
| 7 \(Black\) | IO\_CH6 | +3.3V |
| 8 \(Black\) | IO\_CH7 | +3.3V |
| 9 \(Black\) | IO\_CH8 | +3.3V |
| 10\(Black\) | GND | GND |

#### **FMU Debug Port** \(JST SH 1mm Pitch\) {#fmu-debug-port-jst-sh-1mm-pitch}

| Pin | Signal | Voltage |
| :--- | :--- | :--- |
| 1\(red\) | FMU\_VDD\_3V3 | +3.3V |
| 2 black\) | FMU\_USART3\_TX | +3.3V |
| 3\(black\) | FMU\_USART3\_RX | +3.3V |
| 4\(black\) | FMU\_SWD\_IO | +3.3V |
| 5\(black\) | FMU\_SWD\_CK | +3.3V |
| 6\(black\) | SPI6\_SCK\_EXTERNAL1 | +3.3V |
| 7\(black\) | NFC\_GPIO | +3.3V |
| 8\(black\) | PH11 | +3.3V |
| 9\(black\) | FMU\_nRST | +3.3V |
| 10\(black\) | GND | GND |

#### **I/O Debug Port** \(JST SH 1mm Pitch\) {#i-o-debug-port-jst-sh-1mm-pitch}

| Pin | Signal | Voltage |
| :--- | :--- | :--- |
| 1\(red\) | IO\_VDD\_3V3 | +3.3V |
| 2 black\) | IO\_USART1\_TX | +3.3V |
| 3\(black\) | \(NOT CONNECTED\) | -- |
| 4\(black\) | IO\_SWD\_IO | +3.3V |
| 5\(black\) | IO\_SWD\_CK | +3.3V |
| 6\(black\) | IO\_SWO | +3.3V |
| 7\(black\) | IO\_SPARE\_GPIO1 | +3.3V |
| 8\(black\) | IO\_SPARE\_GPIO2 | +3.3V |
| 9\(black\) | IO\_nRST | +3.3V |
| 10\(black\) | GND | GND |




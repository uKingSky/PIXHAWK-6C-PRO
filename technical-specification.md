# Technical Specification

### **Processors & Sensors** {#processors-and-sensors}

* FMU Processor: STM32H743

  * 32 Bit Arm® Cortex®-M7, 480MHz, 2MB memory, 1MB SRAM

* IO Processor: STM32F103

  *  32 Bit Arm® Cortex®-M3, 72MHz, 64KB SRAM

* On-board sensors

  *  Accel/Gyro: ICM-42688-P

  * Accel/Gyro: BMI055

  * Mag: IST8310

  * Barometer: MS5611

### **Electrical data** {#electrical-data}

* Voltage Ratings:

  * Max input voltage: 6V

  * USB Power Input: 4.75~5.25V

  * Servo Rail Input: 0~36V

* Current Ratings:

  * Telem1 Max output current limiter: 1.5A

  * All other port combined output current limiter: 1.5A

### **Mechanical data** {#mechanical-data}

* Dimensions: 84.8 \* 44 \* 12.4 mm

* Weight \(Aluminum Case\) : 59.3g

* Weight \(Plastic Case\) : 34.6g

### **Interfaces** {#interfaces}

* 16- PWM servo outputs \(8 from IO, 8 from FMU\)

* 3 general purpose serial ports

  * Telem1 - Full flow control, separate 1.5A current limit

  * Telem2 - Full flow control

  * Telem3

* 2 GPS ports

  * GPS1 - Full GPS port \(GPS plus safety switch\)

  * GPS2 - Basic GPS port

* 1 I2C port

  * Supports dedicated I2C calibration EEPROM located on sensor module

* 2 CAN Buses

* 2 Debug port

  * FMU Debug

  * I/O Debug

* Dedicated R/C input for Spektrum / DSM and S.BUS, CPPM, analog / PWM RSSI

* Dedicated S.BUS output

* 2 Power input ports \(Analog\)

### Other Characteristics {#other-characteristics}

* Operating temperature: -40 ~ 85°c




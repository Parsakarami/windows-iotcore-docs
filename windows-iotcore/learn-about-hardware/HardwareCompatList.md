# Hardware compatibility list

Windows 10 IoT Core supports a variety of peripheral interfaces and protocols, including support for common busses like I2C, UART, USB, and more. This page lists known supported peripherals and is current as of the latest RTM release. Specific entries may only work on Insider releases and will be noted as such.

Browse, search, and filter, peripherals that are known to be supported on Windows 10 IoT Core devices. You can also contribute to this list on GitHub by clicking the “Contribute” links.

This list is not exhaustive. There are many other peripherals not listed on this page that are compatible with Windows 10 IoT Core. We encourage you to contribute to this list to improve this resource!

Looking for information about supported hardware platforms? Click [here](https://docs.microsoft.com/en-us/windows-hardware/drivers/gettingstarted/windows-compatible-hardware-development-boards) for a list of development boards compatible with Windows.

## USB Devices

### WiFi Dongles
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|---------------|------------------------------|
> | Official Raspberry Pi WiFi dongle | RPi2/RPi3 | The official Raspberry Pi WiFi dongle offers the best possible WiFi performance for its diminutive size. |[!div class="checklist"] > * |  |
> | Airlink Wireless N 150 Mini USB Adapter Adapter | MBM | Airlink 101 AWL5077 Golden 150Mbps Wireless Mini USB Adapter with WPA2, WPA, and WEP enhanced wireless security | | | 
> | Panda PAU06 | MBM |  Panda 300Mbps Wireless N USB Adapter with High Gain Antenna | | | 
> | TP-LINK TL_WN725N |  RPi2/RPi3, MBM | TP-LINK TL-WN725N Wireless N Nano USB Adapter 150 Mbps `(USB/VID_0BDA&PID_8179)` | | | 
> | NET-DYN USB WiFi Adapter | MBM | WiFi USB Adapter NET-DYN | | | 
> | Realtek 8191 USB Wireless WiFi | RPi2/RPi3, MBM | Realtek 8191 300Mbps 802.11n/g/b/ USB Wireless WiFi LAN Network Card Adapter | | | 
> | Realtek 8192 USB Wireless WiFi | RPi2/RPi3, MBM | Realtek Single-Chip IEEE 802.11b/g/n 2T2R WLAN Controller with USB 2.0 Interface | | |
> | CanaKit USB Wireless WiFi | MBM | Chipset Ralink 5370 | | |

### Bluetooth Dongles
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|--------|------------------------------|
> | CSR Mini USB Blueooth V 4.0 Adapter | RPi2/RPi3, MBM | Class 2 Bluetooth 4.0 Smart Ready Adapter, low energy, dual power | | |
> | ORICO BTA-403 Mini Bluetooth 4.0 USB Dongle | RPi2/RPi3, MBM | Low-energy Bluetooth 4.0 adapter USB Micro Adapter Dongle | | |
> | CSR Mini USB Bluetooth V 4.0 Adapter | MBM | Class 2 Bluetooth 4.0 Smart Ready Adapter, low energy, dual power | | |

### Cameras
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|--------|------------------------------|
> | Microsoft Lifecam 3000 USB Camera | RPi2/RPi3, MBM | USB Webcam | |  [Home Security Camera Project](https://developer.microsoft.com/en-us/windows/iot/samples/webcamapp) | |
> | Microsoft Lifecam HD-5000 | RPi2/RPi3, MBM | Microsoft LifeCam HD-5000 720p HD Webcam | USB 2.0 | |
> | Microsoft® LifeCam Studio™ | RPi2/RPi3 | Microsoft® LifeCam Studio™ (model: 1425) 1080p HD Webcam | USB 2.0 (max. 30 frames per second) | | |
> | Logitech Webcam C210 | RPi2/RPi3, MBM | USB Webcam, 1.3mp photo | | |

### Audio
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|--------|------------------------------|
> | Sabrent USB External Stereo Sound Adapter, Model AU-EMAC1 | RPi2/RPi3, MBM | Converts USB to 3.5mm audio and microphone signals | | |

### Miscellaneous
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links |
> |----------------|-------------------|-------------|--------|------------------------------|
> | Aeon Labs Z-Wave Z-Stick Series 2 USB Dongle DSA02203-ZWUS | RPi2/RPi3 | Series 2 Z-Wave USB Z-Stick Controller | | [ZWave Sample](https://developer.microsoft.com/en-us/windows/iot/samples/zwaveadapter) |
> | Chalkboard Electronics 7” LCD Capacitive Touchscreen Display | RPi2/RPi3 | | [Product Information](https://www.chalk-elec.com/?page_id=1280#!/7-black-frame-universal-HDMI-LCD-with-capacitive-multi-touch/p/21750201/category=3094861)| | [Updating firmware](https://www.chalk-elec.com/?p=1826) |
> | Vodafone (Huawei) K5150 | RPi2/RPi3, MBM | Vodafone (Huawei) K5150 150Mbps 4G LTE FDD USB Mobile Broadband Modem | | | 
> | Sierra Wireless Beam (AirCard 340U) | MBM | 	Sierra Wireless Beam (AirCard 340U) 4G LTE USB Mobile Broadband Modem | | |
> | Microsoft Xbox 360 Controller | RPi2/RPi3 | An HID-compliant USB gamepad for Microsoft's Xbox 360 | | [Robot Kit](https://microsoft.hackster.io/en-US/windowsiot/robot-kit-6dd474) | Access using [HidDevice](https://docs.microsoft.com/en-us/uwp/api/Windows.Devices.HumanInterfaceDevice.HidDevice) (not [Gamepad](https://docs.microsoft.com/en-us/uwp/api/Windows.Gaming.Input.Gamepad)) | 
> | MyTeletouch | RPi2/RPi3 | An HID-compliant USB wireless mouse, keyboard and gamepad | | MyTeletouch Page (http://myteletouch.com/) | Access using your phone (Iphone, Android, Windows) |

## Other Hardware Peripherals

### Storage Media
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links |
> |----------------|-------------------|-------------|--------|------------------------------|
> | Samsung 32GB EVO Class 10 Micro SDHC | RPi2/RPi3, MBM | An SD card that’s known to support running Windows 10 IoT Core on both the Raspberry Pi 2 or 3 and MBM. | | [Amazon Product Info](https://www.amazon.com/gp/product/B00IVPU786) |
> | SanDisk Ultra Micro SDHC 16GB | RPi2/RPi3, MBM | An SD card that’s known to support running Windows 10 IoT Core on both the Raspberry Pi 2 or 3 and MBM. | |  [Amazon Product Info](https://www.amazon.com/SanDisk-Ultra-Micro-SDHC-16GB/dp/9966573445) | 

### Pi Hats
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|--------|------------------------------|
> | [Adafruit 16-Channel PWM](https://www.adafruit.com/product/2327#description-anchor) | RPi2/RPi3 | Adds the capability to control up to 16 servos with no additional Raspberry Pi processing overhead. Capable of doing PWM up to 1.6KHz with 12 bit precision. | | [Adafruit Tutorial C# IoT Sample](https://github.com/golaat/Adafruit.Pwm) | 
> | [Dexter Industries GrovePi](https://www.dexterindustries.com/shop/grovepi-board/) | RPi2/RPi3 | You can connect hundreds of different sensors without soldering, so you can program them to monitor, control, and automate devices in your life. | | [GrovePi Samples](https://github.com/DexterInd/GrovePi/) |
> | Dexter Industries GoPiGo | RPi2/RPi3 | The GoPiGo is a delightful and complete robot for the Raspberry Pi that turns your Pi into a fully operating robot. GoPiGo is a mobile robotic platform for the Raspberry Pi developed by Dexter Industries. | | [GoPiGo Samples](https://github.com/DexterInd/GoPiGo/tree/master/Software/CSharp) |
> | [FEZ HAT](https://www.ghielectronics.com/catalog/product/500) | RPi2/RPi3 | The FEZ HAT allows for a Fast and Easy (FEZ) way to connect all kinds of sensors and devices to the Raspberry Pi. The FEZ HAT is compatible with the RPi 2 Model B. An entire C# driver is provided for immediate use with Windows 10. || [Azure Integration Sample](https://www.ghielectronics.com/docs/329/fez-hat-developers-guide) |
> | [FEZ Cream](https://www.ghielectronics.com/catalog/product/541) | RPi2/RPi3 | The FEZ Utility allows for a Fast and Easy (FEZ) way to connect all kinds of sensors and devices to the Raspberry Pi using on-board headers. It also includes the circuitry needed to provide PWM outputs and analog inputs. The FEZ Utility is compatible with the RPi 2 Model B. An entire C# driver is provided for immediate use with Windows 10. | | [Developer's Guide](https://www.ghielectronics.com/docs/332/fez-utility-developers-guide) |

### Sensors
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|--------|------------------------------|
> | DHT11 basic temperature-humidity sensor | RPi2/RPi3, MBM | A basic, ultra low-cost digital temperature and humidity sensor. It uses a capacities humidity sensor and a thermistor to measure the surrounding air, and spits out a digital signal on the data pin (no analog input pins needed).  | | [GpioOneWireSample (DHT11)](https://developer.microsoft.com/en-us/windows/iot/samples/gpioonewire)|
> | DHT22 temperature-humidity sensor | RPi2/RPi3, MBM | A basic, ultra low-cost digital temperature and humidity sensor. It uses a capacities humidity sensor and a thermistor to measure the surrounding air, and spits out a digital signal on the data pin (no analog input pins needed).  | | [GpioOneWireSample (DHT11)](https://developer.microsoft.com/en-us/windows/iot/samples/gpioonewire) | 
> | SparkFun Triple Axis Accelerometer Breakout - ADXL345 | RPi2/RPi3, MBM | Small, thin, low power, 3-axis MEMS accelerometer with high resolution (13-bit) measurement at up to ±16 g. Digital output data is formatted as 16-bit twos complement and is accessible through either a SPI (3- or 4-wire) or I2C digital interface. | | [I2C Accelerometer Sample](https://developer.microsoft.com/en-us/windows/iot/Samples/I2CAccelerometer.htm#I2C_Accelerometer) |
> | Adafruit BMP280 Temperature and Barometric Sensor | RPi2/RPi3 | Bosch environmental sensor with temperature, barometric pressure | |   |
> | [Adafruit TCS34725 Color Sensor](http://www.adafruit.com/products/1334) | RPi2/RPi3 | RGB Color Sensor with IR filter and white LED - TCS34725 | | |
> | Rohm BH1750FVI ambient light sensor | RPi2/RPi3 | Small I2C sensor for ambient light measurement | | [I2C Samples](https://github.com/mickut/Win10-IoT-Sensors) |
> | Bosch BMP180 temperature and barometric sensor | RPi2/RPi3 | Bosch environmental sensor with tempreature, barometric pressure | | [I2C Samples](https://github.com/mickut/Win10-IoT-Sensors) |
> | Dorji DSTH01 relative humidity sensor | RPi2/RPi3 | I2C relative humidity sensor | | [I2C Samples](https://github.com/mickut/Win10-IoT-Sensors)|
> | Honeywell HMC5883L digital 3-axis compass/magnetometer | RPi2/RPi3 | A small 3-axis magnetometer for digital compass use and magnetic field measurements | | [I2C Samples](https://github.com/mickut/Win10-IoT-Sensors) |

### Port Expanders
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|--------|------------------------------|
> | MCP23008 8-bit I/O Port Expander | RPi2/RPi3, MBM | I2C Interface Chip, GPIO Port Expander. 8 ports, 18-PDIP package | | [I2C Port Explander Sample](https://www.hackster.io/4803/i2c-port-expander-sample-0a6d4f) |
> | MCP23S17 16-bit I/O Port Expander | RPi2/RPi3, MBM | I2C Interface Chip, GPIO Port Expander. 16 ports, 28-SPDIP package | | [Interactive Piano sample](https://www.hackster.io/windowsiot/build-2014-piano-3b449c) |

### NFC/RFID/Proximity
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|--------|------------------------------|
> | NXP OM5577 demo board | RPi2/RPi3 | Demo board for the NXP PN7120 NFC chip. | | [ProximityDevice documentation](https://docs.microsoft.com/en-us/uwp/api/Windows.Networking.Proximity.ProximityDevice) |
> | NXP PN547/PN548/PN7120 | RPi2/RPi3, MBM | Supported NXP NFC chips. | | |

### Miscellaneous
> | Part Name / No. | Compatible Boards | Description | Microsoft Verified | Relevant Links | 
> |----------------|-------------------|-------------|--------|------------------------------|
> | Monochrome 1.3” 128x64 OLED graphic display | RPi2/RPi3, MBM | 1.3” diagonal, high contrast B/W OLED display. 128x64 individual white OLED pixels, each one is turned on or off by the controller chip. | | [SPI Display Sample](https://developer.microsoft.com/en-us/windows/iot/samples/spidisplay) |
> | SN74HC595N Shift Register IC | RPi2/RPi3, MBM | IC 8-BIT SHIFT REGISTER 16-DIP | | [Shift Register Sample](https://developer.microsoft.com/en-us/windows/iot/Samples/shiftregister) |
> | Microchip Technology ADC MCP3002-I/P | RPi2/RPi3, MBM | MCP3002 10bit Analog to Digital converter. ||  [Potentiometer Sensor Sample](https://developer.microsoft.com/en-us/windows/iot/samples/potentiometer) |
> | Microchip Technology ADC MCP3208-CI/P | RPi2/RPi3, MBM | MCP3208 12bit Analog to Digital converter. | | [Potentiometer Sensor Sample](https://developer.microsoft.com/en-us/windows/iot/samples/potentiometer) |
> | ADS1115 | RPi2/RPi3, MBM | Ultra-small, low-power, 16-bit ADC | | [ADC Bus Providers](https://github.com/ms-iot/BusProviders/tree/develop/ADC) |
> | CP2102 USB 2.0 to TTL Module Serial Converter | RPi2/RPi3, MBM | CP2102 USB 2.0 to TTL Module Serial Converter | | [Serial Port Sample](https://developer.microsoft.com/en-us/windows/iot/Samples/serialuart) |
> | PCA9685 | RPi2/RPi3, MBM | 16-channel, 12-bit PWM Fm+ I2C-bus LED controller. | | [PWM Bus Providers](https://github.com/ms-iot/BusProviders/tree/develop/PWM) |

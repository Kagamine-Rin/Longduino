# Longduino

## How to use

### PlatformIO
Only need add follow line into `platformio.ini`
```ini 
platform_packages = framework-arduino-gd32v @ https://github.com/sipeed/Longduino.git
```
### Arduino IDE

Add follow url into `Boards Manager URLs`.
```
http://bigbits.oss-cn-qingdao.aliyuncs.com/Arduino_for_GD32V/package_longduino_index.json
```
## TODO List

### Arduino core

#### wiring_digital.c
* ~~pinMode~~
* ~~digitalWrite~~
* ~~digitalRead~~ @Ldream
* ~~digitalToggle~~ @Ldream

#### wiring_analog.c
* ~~analogRead~~ @ReinForce-II
* ~~analogRefe1rence~~ @ReinForce-II
* ~~analogWrite~~ @ReinForce-II

#### wiring_pulse.c
* ~~pulseIn~~ @ReinForce-II
* ~~pulseInLong~~ @ReinForce-II

#### wiring_shift.c
* ~~shiftIn~~ @ReinForce-II
* ~~shiftOut~~ @ReinForce-II

#### WInterrupts.c
* ~~attachInterrupt~~ @ReinForce-II
* ~~attachInterruptParam~~ @ReinForce-II
* ~~detachInterrupt~~ @ReinForce-II

#### Tone.cpp
* tone
* noTone

#### WMath.cpp
* ~~random~~ @ReinForce-II
* ~~randomSeed~~ @ReinForce-II

#### HardwareSerial.cpp
* Class HardwareSerial

### Libraries
* Wire
* ~~SPI~~ @ReinForce-II
* LCD (Graphics library, need SPI)
* SD (need SPI)
* Ticker
* I2S
* ...

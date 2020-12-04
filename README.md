# AIPlant
Various versions of the AI Plant Arduino Sketch

## ArduinoSketchBasic
The Basic version assumes just a capacitive moisture sensor is attached to the ESP8266 on the pin specified in the code and periodically sends moisture data only, to the Watson IoT platform

## ArduinoSketchWithDHT12
As above but assumes a DHT12 sheild (Wemos/Lolin shield) is attached to the ESP8266 and temperture and humidty data is also sent

## ArduinoSketchWithLEDMatrixAndDHT12
As above but assumes a LED Matrix shield (Wemos/Lolin shield) is attached to the ESP8266 and data is displayed on the matrix with emohis for how wet ot dry the plant is.

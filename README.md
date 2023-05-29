# ZigBee-TuYa-WSD500A

Temperature and Huidity Sensor
* https://smarthomescene.com/reviews/tuya-temperature-humidity-sensor-wsd500a/
* https://www.zigbee2mqtt.io/devices/WSD500A.html#tuya-wsd500a

## Noteable Components

### TuYA ZTU 
* https://developer.tuya.com/en/docs/iot/ztu-module-datasheet?id=Ka45nl4ywgabp
* https://solution.tuya.com/hardware/detail/61005

### CHT8305 
* http://en.sensylink.com/a/products/lm2/CHT8305.html

## Connections

Pin Header
| Pin | ZTU | Function
|-----|-----|-----------
| 1 | ZTU.18 | /RST
| 2 | ZTU.4 |  Burning / SWS
| 3 | ZTU.14 | Bat+ Vcc
| 4 | ZTU.13 | GND (! Not Bat- !)
| 5 | ZTU.15 | B1 Uart_TXD
| 6 | ZTU.16 | B7 Uart_RXD

Sensor
| Pin | Function | ZTU
|-----|----------|-----
| 1 | AD0 | GND
| 2 | VCC |
| 3 | SCL | ZTU.9
| 4 | SDA | ZTU.8
| 5 | GND |
| 6 | ALERT | ZTU.2

ZTU
| Pin | Function|
|-----|----------|
| 3 | Reset Button |

??? Bat- is switched via Q1 (labelled as S2 to GND)

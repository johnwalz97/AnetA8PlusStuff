# Pinout for the Atmega328P
-----------------------------------------------------------------------------------

* NB: Some of these may be different than stock since I have somehwat modified my board

| References/Name           | Number | Function | ?   | ?   | Signal | Extra       |
| ------------------------- | ---    | -------- | --- | --- | ------ | ----------- |
| PCINT0 / ADC0 / PA0       | 37     | SD-SS    | T21 | D31 | A0     |             |
| PCINT1 / ADC1 / PA1       | 36     | EXT-A1   | T47 | D30 | A1     |             |
| PCINT2 / ADC2 / PA2       | 35     | EXT-A2   | T45 | D29 | A2     |             |
| PCINT3 / ADC3 / PA3       | 34     | EXT-A3   | T49 | D28 | A3     |             |
| PCINT4 / ADC4 / PA4       | 33     | EXT-A4   | T51 | D27 | A4     | LED_BUILTIN |
| PCINT5 / ADC5 / PA5       | 32     | Z_ENABLE | T17 | D26 | A5     |             |
| PCINT6 / ADC6 / PA6       | 31     | END_TEMP | T53 | D25 | A6     |             |
| PCINT7 / ADC7 / PA7       | 30     | BED_TEMP | T55 | D24 | A7     |             |

| References/Name           | Number | Function | ?   | ?   | Signal | Extra       |
| ------------------------- | ---    | -------- | --- | --- | ------ | ----------- |
| PCINT8 / XCK0/T0 / PB0    | 40     | E-DIR    | T5  | D0  |        |             |
| PCINT9 / CLKO/T1 / PB1    | 41     | E-STEP   | T7  | D1  |        |             |
| PCINT10 / INT2/AIN0 / PB2 | 42     | Z-DIR    | T3  | D2  | INT2   |             |
| PCINT11 / OC0A/AIN1 / PB3 | 43     | Z-STEP   | T1  | D3  | PWM    |             |
| PCINT12 / OC0B/SS / PB4   | 44     | FAN      | T35 | D4  | PWM    | SS          |
| PCINT13 / MOSI / PB5      | 1      | MOSI     | T25 | D5  |        | MOSI        |
| PCINT14 / MISO / PB6      | 2      | MISO     | T27 | D6  |        | MISO        |
| PCINT15 / SCK / PB7       | 3      | SCK      | T23 | D7  |        | SCK         |

| References/Name           | Number | Function | ?   | ?   | Signal | Extra       |
| ------------------------- | ---    | -------- | --- | --- | ------ | ----------- |
| PCINT16 / SDL / PC0       | 19     | EXT-SCL  | T39 | D16 |        | SCL         |
| PCINT17 / SDA / PC1       | 20     | EXT-SDA  | T37 | D17 |        | SDA         |
| PCINT18 / TCK / PC2       | 21     | X-STOP   | T61 | D18 |        | TCK         |
| PCINT19 / TMS / PC3       | 22     | Y-STOP   | T57 | D19 |        | TMS         |
| PCINT20 / TDO / PC4       | 23     | Z-STOP   | T59 | D20 |        | TDO         |
| PCINT21 / TDI / PC5       | 24     | X-DIR    | T13 | D21 |        | TDI         |
| PCINT22 / TOSC1 / PC6     | 25     | Y-STEP   | T9  | D22 |        |             |
| PCINT23 / TOSC2 / PC7     | 26     | Y-DIR    | T11 | D23 |        |             |

| References/Name           | Number | Function | ?   | ?   | Signal | Extra       |
| ------------------------- | ---    | -------- | --- | --- | ------ | ----------- |
| PCINT24 / RXD0 / PD0      | 9      | AIEO     |     | D8  |        | RX0         |
| PCINT25 / TXD0 / PD1      | 10     | AOEI     |     | D9  |        | TX0         |
| PCINT26 / INT0 / PD2      | 11     | EXT-RX1  | T43 | D10 | INT0   | RX1         |
| PCINT27 / INT1 / PD3      | 12     | EXT-TX1  | T41 | D11 | INT1   | TX1         |
| PCINT28 / OC1B / PD4      | 13     | HOTBED   | T31 | D12 | PWM    |             |
| PCINT29 / OC1A / PD5      | 14     | HOTEND   | T29 | D13 | PWM    |             |
| PCINT30 / OC2B/ICP / PD6  | 15     | XY-ENABL | T19 | D14 | PWM    |             |
| PCINT31 / OC2A / PD7      | 16     | X-STEP   | T15 | D15 | PWM    |             |
The code for flashing the Arduino nano firmware is stored here. A device for maintaining the temperature of the heater.
[OLED]       0.91` 128x32    [Arduino]
 | SDA -> A4       |
 | SCL -> A5       | 
 | VCC -> 5V       |
 | GND -> GND      |

[MAX6675]        [Arduino]
 | CLK  -> D13     |
 | DATA -> D12     |
 | CS   -> D10     |
 | VCC  -> 5V      |
 | GND  -> GND     |

[Кнопки]         [Arduino]
 | MENU  -> D3     |
 | LEFT  -> D7     |
 | RIGHT -> D5     |
 | OK    -> D2     |
 | HEATER-> D4     |
 | Все к GND       |
 [Нагреватель] твердотельное реле
 | + -> D9         |
 | -   GND         |
 

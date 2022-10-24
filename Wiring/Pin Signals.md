Main Board (J1):
| Pin | Signal | Notes |
| :---: | :---: | :---: |
|  1 | P4_USB_DP_OUT | D+ signal from Xbox Motherboard for P4 controller port, or D+ from Programming Board |
|  2 | FUSED +5V | 500 mA fuse for External USB |
|  3 | P3_USB_DP_OUT | D+ signal from Xbox Motherboard for P3 controller port, or D+ from Programming Board |
|  4 | OGX_DISABLE | Signal to activate/deactive OGX360 mod |
|  5 | P2_USB_DP_OUT | D+ signal from Xbox Motherboard for P2 controller port, or D+ from Programming Board |
|  6 | P4_USB_DN | D- signal from Xbox Motherboard for P4 controller port, or D- from Programming Board |
|  7 | P1_USB_DP_OUT | D+ signal from Xbox Motherboard for P1 controller port, or D+ from Programming Board |
|  8 | P3_USB_DN | D- signal from Xbox Motherboard for P3 controller port, or D- from Programming Board |
|  9 | P4_USB_DP_IN | D+ signal from OGX360 to P4 controller port |
| 10 | P2_USB_DN | D- signal from Xbox Motherboard for P2 controller port, or D- from Programming Board |
| 11 | P3_USB_DP_IN | D+ signal from OGX360 to P3 controller port |
| 12 | P1_USB_DN | D- signal from Xbox Motherboard for P1 controller port, or D- from Programming Board |
| 13 | P2_USB_DP_IN | D+ signal from OGX360 to P2 controller port |
| 14 | USB_DP | D+ Signal from Programming Board (not external USB board) |
| 15 | P1_USB_DP_IN | D+ signal from OGX360 to P1 controller port |
| 16 | USB_DN | D- Signal from Programming Board (not external USB board) |
| 17 | +5V | From Controller connector on Xbox motherboard |
| 18 | GND | Common Ground |
| 19 | +5V | From Controller connector on Xbox motherboard |
| 20 | GND | Common Ground |




MiddleMan Boards (both) (J1):
| Pin | Signal P1/P2 | Signal P3/P4 | Notes |
| :---: | :---: | :---: | :---: |
|  1 | +5V | +5V | +5V from Xbox Motherboard to provide power to OGX360i |
|  2 | GND | GND | GND to Motherboard |
|  3 | P1_USB_DN | P3_USB_DN | D- from P1/P3 front panel and Xbox Motherboard to OGX360i |
|  4 | P1_USB_DP | P3_USB_DP | D+ from P1/P3 Front panel to OGX360i |
|  5 | P1_USB_DP_OUT | P3_USB_DP_OUT | D+ from OGX360i to P1/P3 Xbox Motherboard |
|  6 | P2_USB_DN | P4_USB_DN | D- from P2/P4 front panel and Xbox Motherboard to OGX360i |
|  7 | P2_USB_DP | P4_USB_DP | D+ from P2/P4 Front panel to OGX360i |
|  8 | P2_USB_DP_OUT | P4_USB_DP_OUT | D+ from OGX360i to P1/P3 Xbox Motherboard |




External USB Board (J2):
| Pin | Signal | Notes |
| :---: | :---: | :---: |
|  1 | +5V | Fused +5V from OGX360i |
|  2 | USB_DN | D- From USB Port to OGX360i |
|  3 | USB_DP | D+ From USB Port to OGX360i |
|  4 | +3v3 | NOT CONNECTED   No Longer used... |
|  5 | OGX_DISABLE | Signal to OGX360i to enable/disable mod |
|  6 | GND | Common Ground |




*OPTIONAL*
Programming Board (J1):
| Pin | Signal | Notes |
| :---: | :---: | :---: |
|  1 | P4_USB_DP | D+ signal from USB to P4 ATMEGA32U4 Chip |
|  2 | +5V | +5V from USB to power OGX360i |
|  3 | P3_USB_DP | D+ signal from USB to P3 ATMEGA32U4 Chip |
|  4 | OGX_DISABLE | Signal from switch to activate/deactive OGX360 mod |
|  5 | P2_USB_DP | D+ signal from USB to P2 ATMEGA32U4 Chip |
|  6 | P4_USB_DN | D- signal from USB to P4 ATMEGA32U4 Chip |
|  7 | P1_USB_DP | D+ signal from USB to P1 ATMEGA32U4 Chip |
|  8 | P3_USB_DN | D- signal from USB to P3 ATMEGA32U4 Chip |
|  9 | NC | NOT CONNECTED |
| 10 | P2_USB_DN | D- signal from USB to P2 ATMEGA32U4 Chip |
| 11 | NC | NOT CONNECTED |
| 12 | P1_USB_DN | D- signal from USB to P1 ATMEGA32U4 Chip |
| 13 | NC | NOT CONNECTED |
| 14 | NC | NOT CONNECTED |
| 15 | NC | NOT CONNECTED |
| 16 | NC | NOT CONNECTED |
| 17 | NC | NOT CONNECTED |
| 18 | GND | Common Ground |
| 19 | NC | NOT CONNECTED |
| 20 | GND | Common Ground |

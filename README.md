# ShoRa

## About The Project.

ShoRa is just short range pcb where you turn on led using RF signals in the **AIR**. Project is just nonsense because you can do that using 2 wires and 1 mcu. Just some overkill lol

## PHOTOS

<img width="1160" height="508" alt="Zrzut ekranu 2026-06-23 173438" src="https://github.com/user-attachments/assets/2bc90f23-62b2-494a-bd02-7ff2ff1961f6" />
<img width="1243" height="879" alt="schematic" src="https://github.com/user-attachments/assets/a16d4288-fae1-47ac-b8c5-f6e4fb8d42c4" />
<img width="1243" height="879" alt="schematic" src="https://github.com/user-attachments/assets/e5b7410e-1738-4c00-aa5c-da1845dff183" />




## BOM

| Nr | Ref                                     | Value             | Footprint                                                | Qty |
| -: | --------------------------------------- | ----------------- | -------------------------------------------------------- | --: |
|  1 | C1                                      | 100nF             | C_0603_1608Metric                                        |   1 |
|  2 | C2                                      | 2200uF            | CP_Radial_D16.0mm_P7.50mm                                |   1 |
|  3 | C3                                      | 0.33uF            | C_0603_1608Metric                                        |   1 |
|  4 | C4                                      | 10uF              | CP_Radial_D5.0mm_P2.00mm                                 |   1 |
|  5 | R1, R4, R5                              | 100K              | R_2010_5025Metric                                        |   3 |
|  6 | R2, R3                                  | 51k               | R_2010_5025Metric                                        |   2 |
|  7 | R6, R7                                  | 470               | R_2010_5025Metric                                        |   2 |
|  8 | R8                                      | 1                 | R_2010_5025Metric                                        |   1 |
|  9 | D1                                      | GBU4M             | Diode_Bridge_Vishay_GBU                                  |   1 |
| 10 | U1                                      | TL494             | DIP-16_W7.62mm                                           |   1 |
| 11 | U2                                      | LM7824_TO220      | TO-220-3_Vertical                                        |   1 |
| 12 | Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10 | IRF3205           | TO-220-3_Vertical                                        |  10 |
| 13 | Q11                                     | TIP2955           | TO-218-3_Vertical                                        |   1 |
| 14 | T1                                      | 12-230            | Transformer_CHK_EI30-2VA_2xSec                           |   1 |
| 15 | T2                                      | Transformer_1P_1S | Transformer_37x44                                        |   1 |
| 16 | J1                                      | 12VDC             | TerminalBlock_Phoenix_MKDS-1,5-2_1x02_P5.00mm_Horizontal |   1 |
| 17 | J2                                      | 24V               | TerminalBlock_Phoenix_MKDS-1,5-2_1x02_P5.00mm_Horizontal |   1 |

# ShoRa

## About The Project.

ShoRa is just short range pcb where you turn on led using RF signals in the **AIR**. Project is just nonsense because you can do that using 2 wires and 1 mcu. Just some overkill lol

## PHOTOS

<img width="1160" height="508" alt="Zrzut ekranu 2026-06-23 173438" src="https://github.com/user-attachments/assets/2bc90f23-62b2-494a-bd02-7ff2ff1961f6" />
<img width="1243" height="879" alt="schematic" src="https://github.com/user-attachments/assets/a16d4288-fae1-47ac-b8c5-f6e4fb8d42c4" />
<img width="1243" height="879" alt="schematic" src="https://github.com/user-attachments/assets/e5b7410e-1738-4c00-aa5c-da1845dff183" />




## BOM



|   Lp. | References              | Value                         | Footprint                               |   Quantity |
|------:|:------------------------|:------------------------------|:----------------------------------------|-----------:|
|     1 | C3, C4, C6, C8, C9, C10 | 100nF                         | C_0603_1608Metric                       |          6 |
|     2 | C5, C7, C11             | 1uF                           | C_0603_1608Metric                       |          3 |
|     3 | C1, C2                  | 10uF                          | C_0603_1608Metric                       |          2 |
|     4 | R4, R5, R10, R11        | 470                           | R_0603_1608Metric                       |          4 |
|     5 | R1, R2                  | 5.1k                          | R_0603_1608Metric                       |          2 |
|     6 | R3, R9                  | 100k                          | R_0603_1608Metric                       |          2 |
|     7 | R6, R8                  | 10k                           | R_0603_1608Metric                       |          2 |
|     8 | R7                      | 560                           | R_0603_1608Metric                       |          1 |
|     9 | L1, L2                  | L_Ferrite                     | L_0603_1608Metric                       |          2 |
|    10 | D1                      | BLUE                          | LED_2512_6332Metric                     |          1 |
|    11 | U1, U5                  | STM32L051K8Tx                 | LQFP-32_7x7mm_P0.8mm                    |          2 |
|    12 | U2, U4                  | RFM69HCW                      | HOPERF_RFM9XW_THT                       |          2 |
|    13 | U3                      | AMS1117-3.3                   | SOT-223-3_TabPin2                       |          1 |
|    14 | SW1                     | SW_Push                       | SW_PUSH_6mm_H4.3mm                      |          1 |
|    15 | AE1, AE2                | Antenna                       | TestPoint_THTPad_D2.0mm_Drill1.0mm      |          2 |
|    16 | J1, J5                  | Conn_ARM_JTAG_SWD_10          | PinHeader_2x05_P1.27mm_Vertical         |          2 |
|    17 | J3, J4                  | USART                         | PinHeader_1x03_P2.54mm_Vertical         |          2 |
|    18 | J2                      | USB_C_Receptacle_PowerOnly_6P | USB_C_Receptacle_Amphenol_12401610E4-2A |          1 |

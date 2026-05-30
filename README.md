[BOM_macropad.csv](https://github.com/user-attachments/files/28414347/BOM_macropad.csv)# Macro_Pad
## Macropad with 7 switches and a rotary encoder
Table of contents
-The idea
---
-PCB
---
-Schematic
---
-Case
---
-BOM
---
 # The Idea
 ### I've always wanted my own custom macropad , it's a fun thing to have on your desk, it's really convenient to use and the list is endless. I was recently scrolling through yt looking for ideas and possible options to make one myself and boom , I committed to the project.
 # PCB
 
 <img width="1035" height="857" alt="image" src="https://github.com/user-attachments/assets/d2ea1c55-9ebf-47b5-85cb-c3831af9e4c7" />
 
 # Schematic
 
 <img width="1172" height="827" alt="image" src="https://github.com/user-attachments/assets/a273ca2d-dad7-48e5-9d08-d311a35f5d89" />
 
 # Case
 

### They stick together woth magnetic linings on the ledges between the 2 parts and magnets placed between parts , the magnets being hotglued to the component!

##  Bill of Materials (BOM)
[BOM_macropad.csv](https://github.com/user-attachments/files/28414353/BOM_macropad.csv)


Reference | Qty | Value | DNP | Exclude from BOM | Exclude from Board | Footprint | Datasheet | Purchase Link / Notes |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **D1, D2, D3, D4, D5, D6, D7, D8, D9** | 9 | D | *No* | *No* | *No* | Diode_THT:D_DO-41_SOD81_P7.62mm_Horizontal | *None* | [https://in.element14.com/multicomp-pro/1n4148/diode-ultrafast-recovery-150ma/dp/2306361] |
| **SW1** | 1 | RotaryEncoder_Switch | *No* | *No* | *No* | Rotary_Encoder:RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm | *None* | [https://www.flyrobo.in/ec11-rotary-encoder-with-switch-digital-potentiometer-20mm] |
| **SW3, SW4, SW5, SW6, SW7, SW8, SW9, SW10** | 8 | SW_Push | *No* | *No* | *No* | Button_Switch_Keyboard:SW_Cherry_MX_1.00u_PCB | *None* | [https://amzn.in/d/0bjzcqHd] |
| **U1** | 1 | ER_OLEDM0.91_1x-I2C | *No* | *No* | *No* | Display:ER_OLEDM0.91_1x-I2C | [Datasheet PDF](https://www.buydisplay.com/download/manual/ER-OLEDM0.91-1_Datasheet.pdf) | [https://robu.in/product/0-91-inch-128x32-i2c-iic-serial-blue-oled-lcd-display-module/] |
| **U2** | 1 | XIAO-RP2040-DIP | *No* | *No* | *No* | Seeed_Studio_XIAO_Series:XIAO-RP2040-DIP | *None* | [(https://www.wavtron.in/products/seeed-studio-xiao-rp2040)] |
| **N/A** | 1 | MacroPad Case (Top) | *No* | *Yes* | *Yes* | 3D Printed (.3mf File) | *None* | [
] |
| **N/A** | 1 | MacroPad Case (Base) | *No* | *Yes* | *Yes* | 3D Printed (.3mf / .step File) | *None* | [] |
| **N/A** | 2 | Neodymium Magnets | *No* | *Yes* | *Yes* | 4mm x 1.5mm Disc | *None* | [(https://amzn.in/d/00oi9Guo)] *(For snap-fit case alignment)* |


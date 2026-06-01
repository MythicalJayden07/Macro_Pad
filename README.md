# Kyro Vale
## Macropad with 7 switches and a rotary encoder
Table of contents
-The idea

-PCB

-Schematic

-Case

-BOM

 # The Idea
 ### I've always wanted my own custom macropad , it's a fun thing to have on your desk, it's really convenient to use and the list is endless. I was recently scrolling through yt looking for ideas and possible options to make one myself and boom , I committed to the project.
 # PCB
 
 <img width="1035" height="857" alt="image" src="https://github.com/user-attachments/assets/d2ea1c55-9ebf-47b5-85cb-c3831af9e4c7" />
 
 # Schematic
 
 <img width="1172" height="827" alt="image" src="https://github.com/user-attachments/assets/a273ca2d-dad7-48e5-9d08-d311a35f5d89" />
 
 # Case
 <img width="1006" height="524" alt="Screenshot 2026-05-30 064905" src="https://github.com/user-attachments/assets/62ac63ca-ee51-43ef-b0cf-23ab5a452820" />
<img width="1085" height="577" alt="Screenshot 2026-05-30 065930" src="https://github.com/user-attachments/assets/1af2bbcb-6f87-4d3d-b1b9-7f77ccc9bb82" />
<img width="786" height="653" alt="Screenshot 2026-05-30 065947" src="https://github.com/user-attachments/assets/dcadb90e-9c99-4e15-8ffc-e23ccc6afea1" />
<img width="805" height="704" alt="Screenshot 2026-05-30 065958" src="https://github.com/user-attachments/assets/f1176b48-ee31-4453-928b-cbbc48bc1b1f" />
<img width="953" height="718" alt="Screenshot 2026-05-30 070009" src="https://github.com/user-attachments/assets/346ed8f0-0226-4d7a-961b-56fd56d09e6f" />
<img width="730" height="590" alt="Screenshot 2026-05-30 070154" src="https://github.com/user-attachments/assets/2d4bd5bf-ae90-4d2a-9d4d-fc5f3cb08177" />
<img width="642" height="589" alt="Screenshot 2026-05-30 074514" src="https://github.com/user-attachments/assets/f880fb04-c845-4d05-9808-0336f5ed8d19" />
<img width="760" height="577" alt="Screenshot 2026-05-30 074506" src="https://github.com/user-attachments/assets/eee98cf3-5dad-4f77-a1f2-8ecd857fdefa" />


### They stick together with springs that snap the 2 pieces together, rellay cool mechanism i came up with , it alsol has a side handrest!!!

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


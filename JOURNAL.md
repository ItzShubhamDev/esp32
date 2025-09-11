---
Title: "ESP 32 Board"
Author: "Shubham"
Description: "A board for ESP32 S3"
Created On: "5/8/2025"
Total Time: 30h
---

# August 5th: Made the USB-C Input and Voltage regulator!

Did a research on ESP32 S3 boards looked out ESP32 S3 Devkit and it's [schematic](https://dl.espressif.com/dl/SCH_ESP32-S3-DEVKITC-1_V1_20210312C.pdf) to learn about the wiring and made my own USB-C input and a voltage regulator to step down voltage from 5V to 3.3V for safer operation of the chip.
<img width="1533" height="604" alt="image" src="https://github.com/user-attachments/assets/780b7905-380f-4a41-ab62-3d912b28da1c" />
<img width="1043" height="792" alt="image" src="https://github.com/user-attachments/assets/e9a283f0-8f87-4bdf-a776-4609ab1abd8d" />

**Time spent: 4h**

# August 6th: Completed the schematic!

Did a research on safe pins to expose of the board, added Red LED, RGB LED, SD Card Reader, Boot and Reset Buttons and Connections Pins.
<img width="1149" height="821" alt="Screenshot 2025-08-06 182400" src="https://github.com/user-attachments/assets/ff7d9e7f-6e43-441f-ae6e-d767ec6c52aa" />
<img width="1190" height="845" alt="SCH_Schematic1_1-P1_2025-08-07" src="https://github.com/user-attachments/assets/69a48776-d44f-4575-94c9-e10e7659a804" />

**Time spent: 8h**

# August 7th: Modified the schematic and completed 70% routing!

Modified the schematic to make some adjustments to the pins connections and added traces for almost every connection except for the GND and 2-3 more remaining.
<img width="1190" height="845" alt="SCH_Schematic1_1-P1_2025-08-08" src="https://github.com/user-attachments/assets/e36264ce-3eeb-49eb-912d-f8f379f2f3fc" />
<img width="563" height="662" alt="Screenshot 2025-08-07 120754" src="https://github.com/user-attachments/assets/28f4ed77-c2a1-4e54-bb08-329e87d943d9" />
<img width="413" height="695" alt="Screenshot 2025-08-07 140605" src="https://github.com/user-attachments/assets/312f7046-8762-4613-a097-42434b636c08" />
<img width="386" height="673" alt="Screenshot 2025-08-07 155555" src="https://github.com/user-attachments/assets/2a65d6b6-ba9d-4a4e-9144-a02a11c1028e" />
<img width="292" height="545" alt="Screenshot 2025-08-07 231847" src="https://github.com/user-attachments/assets/7a9d1ebf-a7b7-472e-b655-671cc8a05e31" />
<img width="319" height="584" alt="Screenshot 2025-08-07 160420" src="https://github.com/user-attachments/assets/36de6b7a-76eb-4738-bc33-e6fdf901bb7a" />
<img width="495" height="748" alt="Screenshot 2025-08-08 022658" src="https://github.com/user-attachments/assets/72ea1a5c-c7f3-491b-b496-651d9a16b676" />

**Time spent: 6h**

# August 8th: Completed the PCB!

After completing the PCB I went through a final check and the microSD reader wasn't avaiable, so had to replace the microSD reader in schematic and redo that section, also I fixed the wrong pins of the left side of the board and added pin names on the bottom layer.
<img width="677" height="388" alt="Screenshot 2025-08-08 231342" src="https://github.com/user-attachments/assets/688b5f09-bbac-4149-b458-7edbe03792f0" />
<img width="369" height="716" alt="Screenshot 2025-08-08 231325" src="https://github.com/user-attachments/assets/d8aaa93e-fe53-468b-b5fd-dc9d01df4fb7" />
<img width="370" height="690" alt="Screenshot 2025-08-08 231411" src="https://github.com/user-attachments/assets/1b368363-f817-4687-9f54-669c50d30dbc" />
<img width="1098" height="591" alt="Screenshot 2025-08-08 234542" src="https://github.com/user-attachments/assets/8d972161-77f9-4ba6-a3da-a7c909ccad66" />

**Time spent: 6h**

# August 23rd: Replaced ESP32-S3-WROOM with ESP32-S3-IC

After completing all the things, someone suggested me to use ICs instead of Wrooms to gain more knowledge about boards, chips and overall electronics.

<img width="1197" height="847" alt="SCH_Schematic1_1-P1_2025-08-23" src="https://github.com/user-attachments/assets/0adcd4ae-20c3-4bdc-86a7-7944032113d7" />

**Time spent: 2h**

# September 11th: Completed the schematic with the new IC.

I will be using ESP32-S3-PICO-1-N8R8, so made the schematic around that, the hardest part was Antenna, I had to read atleast 5 articles to get some info on the antennas.

<img width="1197" height="845" alt="SCH_Schematic1_1-P1_2025-09-12" src="https://github.com/user-attachments/assets/a75fb6f4-c7f8-4260-8df0-512d80e16f0b" />

**Time spent: 4h**

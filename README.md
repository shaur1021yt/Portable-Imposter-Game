# Portable-Imposter-Game
A handheld gaming retro console with games like imposter and snake as well as many more as well as AI functionality! To use product, flash the code in FirmWare file into the raspberry pico 2w and create a deepseek key on groq to use the ai functionality. Then your all set, add the key into the code and you are ready to play the games that are in the device. You may also code your own games onto the device.

# Why I Made This
Recently we got into playing imposter game whenever we were free from work at school. Imposter game is a game where a group of people get the same word but one person(The imposter) only gets the category of the word, and every person goes in turn to say a clue to convince everyone else that they are not the imposter. It is the imposters goal to figure oout the word, or blend in to not get voted out at the end! We used a website to play this game, but since it was blocked on chromebooks, and the macbook we had available was ENORMOUS, I decided to make this!

Here Are Some Pics of the Project:

Prototype: 

![First working oled](https://github.com/user-attachments/assets/1317f710-0b3a-4d5f-96f6-e2d09966fadf)


Schematic:

<img width="1169" height="843" alt="Schematic_Imposter-Game_2026-03-29" src="https://github.com/user-attachments/assets/7593dc2d-c5c8-4a8a-a535-0e00d7690994" />


PCB:

<img width="479" height="385" alt="PCB_PCB_Imposter-Game_2026-03-29" src="https://github.com/user-attachments/assets/ee079ae6-f00b-4278-b4ab-43e41755622d" />

Full 3D CAD + PCB:

<img width="653" height="476" alt="Screenshot 2026-03-29 at 1 57 05 pm" src="https://github.com/user-attachments/assets/cf3a65a0-294d-425b-b313-30f8bc707389" />

# BOM

| ID | Name | Designator | Footprint | Quantity | Manufacturer Part | Manufacturer | Supplier | Supplier Part | Price | Link |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | RASPBERRY PI PICO 2W | U1 | COMM-SMD_L51.0-W21.0-P2.54_PICOW | 1 | Raspberry Pi Pico 2W | Raspberry Pi(树莓派) | LCSC | C42394205 |  | [Link](https://atta.szlcsc.com/upload/public/pdf/source/20230906/10B4C0665D815973E97A5F4971CA719F.pdf) |
| 2 | NSR0320MW2T1G | D2 | SOD-323_L1.8-W1.3-LS2.5-RD | 1 | NSR0320MW2T1G | onsemi(安森美) | LCSC | C48192 | 0.079 | [Link](https://item.szlcsc.com/295156.html) |
| 3 | 4.7uH | L1 | IND-SMD_L3.5-W3.0 | 1 | CD32N-4R7M | MINGSTAR(登壹) | LCSC | C2875683 | 0.065 | [Link](https://item.szlcsc.com/392683.html) |
| 4 | YLED0805O | LED1 | LED0805-FD-GREEN | 1 | YLED0805O | YONGYUTAI(永裕泰) | LCSC | C25170727 | 0.01 | [Link](https://item.szlcsc.com/datasheet/YLED0805G/26899175.html) |
| 5 | 4.7kΩ | R1,R2 | RES-SMD_L3.5-W1.5 | 2 | MELF-MFR02041/4WS4.7KΩFT50 | Thunder Component(帝谷) | LCSC | C265557 |  | [Link](https://item.szlcsc.com/363256.html) |
| 6 | 20kΩ | R4 | R1206 | 1 | FRC1206F2002TS | FOJAN(富捷) | LCSC | C2933636 | 0.004 | [Link](https://item.szlcsc.com/311874.html) |
| 7 | 330Ω | R5 | R0805 | 1 | CRCW0805330RJNEA | VISHAY(威世) | LCSC | C844209 | 0.026 | [Link](https://item.szlcsc.com/142685.html) |
| 8 | 1kΩ | R6 | R0603 | 1 | APC0603B1K00N | Ohmite | LCSC | C7077186 | 0.233 | [Link](https://www.mouser.in/datasheet/2/447/PYu_RT_1_to_0_01_RoHS_L_11-1669912.pdf) |
| 9 | PEC11R-4015F-S0024 | SW1,SW7 | SW-TH_PEC11R-4XXXF-SXXXX | 2 | PEC11R-4015F-S0024 | BOURNS | LCSC | C143789 | 2.606 | [Link](https://item.szlcsc.com/155120.html) |
| 10 | KH-SS12D10-G9-3.5 | SW2 | SW-TH_KH-SS12D10-G9-3.5 | 1 | KH-SS12D10-G9-3.5 | kinghelm(金航标) | LCSC | C5274458 | 0.161 | [Link](https://atta.szlcsc.com/upload/public/pdf/source/20221118/84F653834E486D1.pdf) |
| 11 | TS-1088-AR02016 | SW3,SW4,SW5,SW6 | SW-SMD_TS-1088 | 4 | TS-1088-AR02016 | XUNPU(讯普) | LCSC | C455280 | 0.053 | [Link](https://www.farnell.com/datasheets/2775479.pdf) |
| 12 | 100nF | C1,C2,C3 | C0603 | 3 | CL10B104KB8NNNC | Samsung | LCSC | C14663 | 0.002 | [Link](https://img.jlc.com/image//data/smt-stock-product/2022/08/23/2D5E6.png) |
| 13 | 10uF | C4,C5 | C0805 | 2 | CL21A106KAYNNNE | Samsung | LCSC | C15850 | 0.01 | [Link](https://jlc-prod-smt-component.oss-cn-shenzhen.aliyuncs.com/product/images/C15850.png) |
| 14 | 1uF | C6 | C0603 | 1 | CL10A105KB8NNNC | Samsung | LCSC | C15849 | 0.003 | [Link](https://img.jlc.com/pdf/applyPasteComponent/2022/03/31/CL10A105KB8NNNC.pdf) |
| 15 | USB-C Connector | J1 | TYPE-C-SMD | 1 | TYPE-C-31-M-12 | Korean Hroparts | LCSC | C165948 | 0.225 | [Link](https://atta.szlcsc.com/upload/public/pdf/source/20220728/TYPEC.pdf) |
| 16 | 1N5819 | D1 | SMA | 1 | SS14 | MCC | LCSC | C319476 | 0.05 | [Link](https://item.szlcsc.com/319476.html) |
| 17 | AMS1117-3.3 | U2 | SOT-223 | 1 | AMS1117-3.3 | AMS | LCSC | C6186 | 0.12 | [Link](https://item.szlcsc.com/323315.html) |
| 18 | 22uF | C7 | C1206 | 1 | CL31A226KAHNNNE | Samsung | LCSC | C12891 | 0.02 | [Link](https://item.szlcsc.com/15869.html) |
| 19 | 10kΩ | R7,R8 | R0603 | 2 | RC0603FR-0710KL | Yageo | LCSC | C98220 | 0.002 | [Link](https://item.szlcsc.com/169042.html) |
| 20 | 5.1kΩ | R9,R10 | R0603 | 2 | RC0603FR-075K1L | Yageo | LCSC | C23186 | 0.002 | [Link](https://item.szlcsc.com/364452.html) |
| 21 | 330Ω | R11 | R0603 | 1 | RC0603FR-07330RL | Yageo | LCSC | C844209 | 0.002 | [Link](https://item.szlcsc.com/142685.html) |

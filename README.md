<h1 align="center">Water Alarm</h1>

<p align="center">
  A simple water detection alarm that warns you early when moisture or leaks are detected.
</p>

---

## About

Water Alarm is a project designed to detect the presence of water and trigger an alert as soon as moisture is found. It can be used in places like bathrooms, basements, kitchens, near sinks, or around any area where water could potentially cause damage.

---

## Features

- Water detection
- Instant alarm response
- Simple and practical design
- Useful for home safety and monitoring
- Loud buzzer alert
- Compact and easy to install
- Drill mounts
- LED light (Optional)

---

## Renders

<p align="center">
  <img src="https://github.com/user-attachments/assets/c38162c2-091c-41da-b59c-7ebeb59c5152" alt="Water Alarm Prototype 1" />
  <img src="https://github.com/user-attachments/assets/85b4b99f-063e-4a32-88e1-14534918d0e5" alt="Water Alarm Prototype 2" />
  <img src="https://github.com/user-attachments/assets/7d23e924-d90f-45f1-a4f8-a6a1a8a4a496" alt="Water Alarm Prototype 3" />
  <img width="989" height="613" alt="image" src="https://github.com/user-attachments/assets/351a7c60-670a-4d45-9d26-3940ad1df14b" />

*Pls look at the files for the engineering drawings, BOM, schematics, etc. for more

</p>

---

## Background

This water alarm can be used anywhere, such as near a toilet, sink, or any place where water could potentially flood. It powers a loud buzzer to notify people of a leak and

It was built using components from DigiKey. Schematics, PCB layout, Gerber files, and testing were completed in KiCad, and the engineering drawings were created for the project.

The project helped develop skills in schematic design, PCB design, soldering, and working with electrical components. I truly encourage anyone to try this out, especially if you are new to PCBs and electronics.

---

## Components

# Bill of Materials

| Reference | Part Number/Links | Value | Footprint | Description | Qty | Cost (USD) |
|---|---|---|---|---|---:|---:|
| BZ1 | [668-1652-ND](https://www.digikey.com/en/products/detail/pui-audio-inc/AI-3035-TT-12V-R/9083403?s=N4IgTCBcDaIGxwBwFoCMcCsZkDkAiIAugL5A) | Buzzer | `1_buzzers:Buzzer_D30mm_H20mm_P15mm_668-1652-ND` | Audible alarm | 1 | $6.99 |
| C1 | [56-K102K10X7RH5UL2CT-ND](https://www.digikey.com/en/products/detail/vishay-beyschlag-draloric-bc-components/K102K10X7RH5UL2/2820341?s=N4IgTCBcDaIKwDYC0BpAjABjOjANA7AEoAScAqgDJgDCAKkgHIAiIA) | 0.001 uF | `Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm` | Capacitor | 1 | $0.13 |
| D2 (V2) | [1830-1004-ND](https://www.digikey.com/en/products/detail/inolux/INL-3AG30/7604619?s=N4IgTCBcDaIIwA4DMAGAtHFKAsaByAIiALoC%2BQA) | LED | `LED_THT:LED_D3.0mm` | Light emitting diode, small green | 1 | $0.39 |
| J1 | [CP-037A-ND](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/PJ-037A/1644545?s=N4IgTCBcDaIMIAUC0AGAzAdgIJIHIBEQBdAXyA) | Barrel Jack | `Connector_BarrelJack:BarrelJack_Horizontal` | Power input jack | 1 | $1.74 |
| J2 | [2057-EBAA-02-C-ND](https://www.digikey.com/en/products/detail/adam-tech/EBAA-02-C/13586872?s=N4IgTCBcDa4AwFYDsBaAogIQIJZXMKAwigHIAiIAugL5A) | Screw Terminal | `TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2_1x02_P5.00mm_Horizontal` | Water sensor connection | 1 | $0.67 |
| Q1 | [4878-2N7000CT-ND](https://www.digikey.com/en/products/detail/diotec-semiconductor/2N7000/13164314?s=N4IgTCBcDaICwA4DsCC0YBySAMuDCAKqhgCIgC6AvkA) | MOSFET | `Package_TO_SOT_THT:TO-92_Inline` | N-channel MOSFET | 1 | $0.47 |
| R1 | [CF18JT10M0CT-ND](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF18JT10M0/1741568?s=N4IgTCBcDaIMIDECMAOAUgFSQBgLLbgwFoA5AERAF0BfIA) | Resistor (10M) | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal` | Pull-down resistor | 1 | $0.10 |
| R2 (V2) | [CF18JT330RCT](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF18JT330R/1741683) | Resistor (330 Ohms) | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal` | LED current limiting resistor | 1 | $0.10 |
| Z1 | [364-1254-ND](https://www.digikey.com/en/products/detail/tri-mag-llc/L6R06H-120/7682617?s=N4IgTCBcDaIMwDYAsBaAjGArKgcgERAF0BfIA) | 12v Supply | — | Housing | 1 | $6.83 |
| Z2 | [1927-1053-ND](https://www.digikey.com/en/products/detail/kitronik-ltd/4132/8635470?s=N4IgTCBcDaIIwE4wHYC0cAMBWAzKgcgCIgC6AvkA) | Batt Assy | — | Battery Assembly (9v) | 1 | $1.28 |
| - | [Link](https://www.walmart.com/ip/Great-Value-9V-Batteries-2-Pack-Alkaline-9-Volt-Batteries/14359618034?wmlspartner=wlpa&selectedSellerId=0&wl13=688&adid=2222222229714359618034_0000000000_23) |  |  |  |  |  |
| - | [Link](https://www.dxengineering.com/parts/dxe-pw-18?seid=dxese1&gad_source=1&gad_campaignid=18666805149&gclid=CjwKCAjwuczWBhA9EiwAYGgEoXRTcK_Nh8_z7XygRpjv3QG3suuSUEusgzB5P-DtU-ECp1jka1wYjRo) |  |  |  |  |  |
|  |  |  |  |  | *Estimated* | **Subtotal: $19.06** |

Refer to BOM.csv as needed

*The quantity shows a minimum number of components needed to create 1 water alarm. I recommend buying more than 1 component, just to have as back up. Costs may differ if done so

---

## Setup

Components will need to be soldered onto the PCB board carefully, especially the MOSFET (Q1). A wire should be connected to the Terminal Block (J2) with both ends of the wire stripped off to reveal the conductive wire.

## Revisions & Changes

-V1 was the board that was physically built, soldered, and tested. V1 did NOT have a functioning LED light, and only had the buzzer

-V1 Issues: D2 anode had no trace to VCC, and R2's pad went to GND, so LED wouldn't have been activated when the alarm was activated

-V2 Changes: D2 anode to VCC, R2 to the Q1 drain, and R2 changed to CF18JT330R

Note: The LED and R2 are completely optional and haven't been tested. The buzzer works without it. I have included both V1 and V2 schematics and PCB screenshots. 

## CAD File  

https://github.com/nishadhmulay/Water-Alarm-/releases/download/V1/Water.Alarm.CAD.1.step

## Engineer Drawings

- [Water Alarm Engineered Drawings (Exploded)](https://github.com/nishadhmulay/Water-Alarm-/blob/main/Water%20Alarm%20Engineered%20Drawings%20%28Exploded%29%20WA1.0.pdf)
- [Water Alarm Engineered Drawings 2](https://github.com/nishadhmulay/Water-Alarm-/blob/main/Water%20Alarm%20Engineered%20Drawings%202.pdf)
- [Water Alarm Dimensions](https://github.com/nishadhmulay/Water-Alarm-/blob/main/Water%20Alarm%20Dimensions.pdf) 

## Wiring Schematics

- [KiCad wiring schematic](https://github.com/nishadhmulay/Water-Alarm-/blob/main/water%20alarm.kicad_sch)

## PCB Editor (KiCad)

- [KiCad PCB layout](https://github.com/nishadhmulay/Water-Alarm-/blob/main/water%20alarm.kicad_pcb)

## Schematic Editor 

- [Schematic Editor](https://github.com/nishadhmulay/Water-Alarm-/blob/main/Schematic%20Editor.png)

---

## Usage

Any 9-volt battery with a barrel plug will work perfectly. The water alarm will continue detecting moisture until the battery lasts (Approx. 1-3 years).

---

## Future Improvements

- 3D printed enclosure
- Adjustable sensitivity
- More wire sensors
- Separated pads for easier soldering

---

## Tips

- Make sure that the solder DOES NOT flow through and connect the pins or pads for the MOSFET (Q1). The solder should cover each independent pad and pin only
- If the buzzer sounds each time the battery is plugged in, check the solder on the back and make sure it's not touching multiple pads/pins. Make sure the wires aren't touching each other
- Don't accidentally place a component the wrong way; always make sure that they follow the outline on the PCB
- Make sure the sensor area stays clean and dry when not in use.
- Test the alarm once in a while to confirm it still works.
- Place the sensor in an area where water would collect first.
- Check all wiring and connections if the alarm is not triggering.
- Replace the battery or power source if the alarm becomes weak.

---

## AI Usage

- Used to figure out how to set the copper area on the PCB
- General definitions and functions of parts, mechanisms, etc.
- Confirming that parts and the entire circuit can work
- Assigning footprints to the LED
- Using and learning GitHub
- Clarifying rules and resources
- Checking for any mistakes in wiring schematics in KiCad
- Learning and tips for soldering

---

## Disclaimer

This project is provided for educational and informational purposes only. Use it at your own risk.

The author is not responsible for any damage, injury, or loss resulting from the use or misuse of this project. This project is not certified for commercial, industrial, or life-safety use.

Always use caution when working with electricity, water, and electronic components.
Good luck!!

<img width="504" height="514" alt="image" src="https://github.com/user-attachments/assets/ad0cb48f-f1ab-4840-b609-02a33af6728a" />

---

## License

This project is open source and available under the MIT License.

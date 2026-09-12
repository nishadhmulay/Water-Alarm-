<h1 align="center">Water Alarm</h1>

<p align="center">
  A simple water detection alarm that warns you early when moisture or leaks are detected.
</p>

<p align="center">
  <a href="#what-is-this">What is this?</a> •
  <a href="#features">Features</a> •
  <a href="#background">Background</a> •
  <a href="#components">Components</a> •
  <a href="#setup">Setup</a> •
  <a href="#cad-file">CAD File</a> •
  <a href="#usage">Usage</a> •
  <a href="#future-improvements">Future Improvements</a> •
  <a href="#license">License</a>
</p>
---

## What is this?

Water Alarm is a project designed to detect the presence of water and trigger an alert as soon as moisture is found. It can be used in places like bathrooms, basements, kitchens, near sinks, or around appliances where leaks may happen.

## Features

- Water detection 
- Instant alarm response
- Simple and practical design
- Useful for home safety and monitoring
- Loud buzzer alert
- Compact and easy to install
- Drill mounts
- LED light trigger

## Renders

<p align="center">
  <img src="https://github.com/user-attachments/assets/c38162c2-091c-41da-b59c-7ebeb59c5152" alt="Water Alarm Prototype 1" />
  <img src="https://github.com/user-attachments/assets/85b4b99f-063e-4a32-88e1-14534918d0e5" alt="Water Alarm Prototype 2" />
  <img src="https://github.com/user-attachments/assets/7d23e924-d90f-45f1-a4f8-a6a1a8a4a496" alt="Water Alarm Prototype 3" />
  <img width="989" height="613" alt="image" src="https://github.com/user-attachments/assets/351a7c60-670a-4d45-9d26-3940ad1df14b" />

*Pls look at the files for the engineering drawings, BOM, schematics, etc. for more

</p>

## Background

This water alarm can be used anywhere. Near a sewer, toilet, sink, or any place where water could potentially flood. It powers a loud buzzer to notify people of a leak.

It was built using components from DigiKey and inspired by DigiKey's water alarm tutorial. Schematics, PCB layout, Gerber files, and testing were completed in KiCad, and the engineering drawings were made in Autodesk Fusion.

The project helped develop skills in schematic design, PCB design, soldering, and working with electrical components. I truly encourage anyone to try this out, especially if you are new to PCBs and electrical components in general. 

## Components

## Bill of Materials

| Reference | DKPN | Value | Footprint | Description | Qty |
|---|---|---|---|---|---|
| BZ1 | 668-1652-ND | Buzzer | `1_buzzers:Buzzer_D30mm_H20mm_P15mm_668-1652-ND_AI-3035-TT-12V-ND` |  | 1 |
| C1 | 56-K102K10X7RH5UL2CT-ND | 1nF | `Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm` | Unpolarized capacitor, small symbol | 1 |
| D2 | 1830-1004-ND | LED_Small_Filled | `LED_THT:LED_D3.0mm` | Light emitting diode, small symbol, filled shape | 1 |
| J1 | CP-037A-ND | Jack-DC | `Connector_BarrelJack:BarrelJack_GCT_DCJ200-10-A_Horizontal` | DC Barrel Jack | 1 |
| J2 | 2057-EBAA-02-C-ND | Screw_Terminal_01x02 | `TerminalBlock_Phoenix:TerminalBlock_Phoenix_PT-1,5-2-5.0-H_1x02_P5.00mm_Horizontal` | Generic screw terminal, single row, 01x02 | 1 |
| Q1 | 4878-2N7000CT-ND | 2N7000 | `Package_TO_SOT_THT:TO-92_Inline` | 0.2A Id, 200V Vds, N-Channel MOSFET | 1 |
| R1 | CF18JT10M0CT-ND | 10M | `Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal` | Resistor, small US symbol | 1 |
| R2 | CF14JT330RTR-ND | 330 Ohms | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal` | Resistor, small US symbol | 1 |
| Z1 | 364-1254-ND | 12v Supply |  | Housing | 1 |
| Z2 | 1927-1053-ND | 9v Batt Assy |  | Multiple-cell battery | 1 |

## Setup

Components will need to be soldered onto the PCB board carefully, especially the MOSFET (Q1). A wire should be connected to the Terminal Block (J2) with both ends of the wire stripped off to reveal two copper-filled wires inside the main wire. The insulation of those two wires inside the main wire is also stripped off to reveal the copper. This is done on both ends, so copper can connect to the terminal block and be tightly screwed on with the screws on the Terminal Block (J2), and water can be detected from the other side of the wire via the stripped copper wire. A 9-volt battery should be securely attached to the barrel plug. The water alarm can be drilled into a surface or secured with zip ties in the 2 holes. 

## Usage

Any 9-volt battery with a barrel plug will work perfectly. The water alarm will continue detecting moisture until the battery lasts (Approx. 1-3 years). 

## Future Improvements

- 3D printed enclosure
- Adjustable sensitivity
- More wire sensors
- Separated pads for easier soldering

## Tips

- Make sure that the solder DOES NOT flow through and connect the pins or pads for the MOSFET (Q1). The solder should cover each independent pad and pin only
- If the buzzer sounds each time the battery is plugged in, check the solder on the back and make sure it's not touching multiple pads/pins. Make sure the wires aren't touching each other
- Don't accidentally place a component the wrong way; always make sure that they follow the outline on the PCB 
- Make sure the sensor area stays clean and dry when not in use.
- Test the alarm once in a while to confirm it still works.
- Place the sensor in an area where water would collect first.
- Check all wiring and connections if the alarm is not triggering.
- Replace the battery or power source if the alarm becomes weak.

## Disclaimer

This project is provided for educational and informational purposes only. Use it at your own risk.

The author is not responsible for any damage, injury, or loss resulting from the use or misuse of this project. This project is not certified for commercial, industrial, or life-safety use.

Always use caution when working with electricity, water, and electronic components. 

Good luck!

<img width="504" height="514" alt="image" src="https://github.com/user-attachments/assets/ad0cb48f-f1ab-4840-b609-02a33af6728a" />

## License

This project is open source and available under the MIT License.

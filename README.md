# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![Screenshot 2025-05-10 160454](https://github.com/user-attachments/assets/7a700f59-c4b4-4006-b791-0a4edf7d1e57)

<img width="765" height="656" alt="Screenshot 2026-02-19 093102" src="https://github.com/user-attachments/assets/a6ee245a-85ef-4b0f-81aa-63b6ea3fa6ed" />


### Schematicand Symbol of 2-Input EX-OR Gate:

<img width="1919" height="1199" alt="Screenshot 2026-02-19 133638" src="https://github.com/user-attachments/assets/16a0d911-1cb6-499f-8bef-e8352ee70e84" />

<img width="1392" height="937" alt="Screenshot 2026-02-19 133626" src="https://github.com/user-attachments/assets/320767ec-b840-4fef-874d-9c61b2669385" />


### Schematicand Symbol of Half Adder:

<img width="1679" height="983" alt="Screenshot 2026-02-19 135156" src="https://github.com/user-attachments/assets/643aec01-3b39-4e6e-9efc-8ca46a8b9eb7" />
<img width="887" height="753" alt="Screenshot 2026-02-19 135144" src="https://github.com/user-attachments/assets/51468432-ea77-4a61-befe-f34835074a38" />


### Schematic of 2-Bit Multiplier:
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/cf87918f-68c3-44a3-babd-61320d1bf37d" />


## Output
### Transient Analysis Output:
<img width="858" height="796" alt="Screenshot 2026-02-20 101947" src="https://github.com/user-attachments/assets/93b607e8-5c18-40a7-8c4e-a09605577ff9" />


![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)


<img width="1919" height="1199" alt="Screenshot 2026-02-20 101902" src="https://github.com/user-attachments/assets/5f9a2140-7f7a-4f9d-9107-e2d6be1d3043" />


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.

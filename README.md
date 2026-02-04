# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. 2:1 MUX USING CMOS
<img width="734" height="589" alt="Screenshot 2025-03-10 101825" src="https://github.com/user-attachments/assets/09a499d0-4d83-4955-97e8-56e12a6a8f4d" />


### 2. Schematic of Full Custom 2:1 MUX

<img width="1600" height="859" alt="image" src="https://github.com/user-attachments/assets/1889c496-62bf-4fc2-b3d8-aa8d6118c1ce" />


### 3. Transient Response Setup

<img width="512" height="601" alt="Screenshot (290)-LAPTOP-4N3VK7RO" src="https://github.com/user-attachments/assets/e05360c6-9398-4e38-8d30-b8fc6b60e58f" />



<img width="866" height="630" alt="image" src="https://github.com/user-attachments/assets/c5521380-222a-4900-a222-774c25912eaa" />


## Output

### 1. Transient Analysis Output

<img width="1600" height="784" alt="image" src="https://github.com/user-attachments/assets/3a59d4bf-39f2-4df8-8529-38fdfd3c1f28" />


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.

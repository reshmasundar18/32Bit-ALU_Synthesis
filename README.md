# EXP-05: 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

• Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)
• Synthesis: Genus

### Step 1: Getting Started

• Synthesis requires three files as follows,
◦ Liberty Files (.lib)
◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh
◦ source /cadence/install/cshrc
• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.
• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![Screenshot 2024-11-24 182231](https://github.com/user-attachments/assets/052b03ce-c4bd-45ba-b433-5f73bfc4361a)

#### Area report:
![Screenshot 2024-11-24 182712](https://github.com/user-attachments/assets/ad0f702e-55b9-4013-96a8-92162f0f0cc6)

#### Power Report:
![Screenshot 2024-11-24 182823](https://github.com/user-attachments/assets/3d09e716-f443-4c55-8fdf-38ba1486a3a9)


#### Result: 
The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.

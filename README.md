# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

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

![Screenshot 2025-05-20 183748](https://github.com/user-attachments/assets/de8a6ab7-dc6f-4b84-99d9-60a16cba2516)

#### Area report:

![Screenshot 2025-05-20 183846](https://github.com/user-attachments/assets/5784b018-bd61-42be-9d50-90a38cc5f01b)

#### Power Report:

![Screenshot 2025-05-20 183839](https://github.com/user-attachments/assets/e7d24781-1b5d-4b56-b750-1cb92a37c0ef)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.

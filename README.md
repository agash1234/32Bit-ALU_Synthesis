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
![WhatsApp Image 2025-05-20 at 22 09 53_00f344a3](https://github.com/user-attachments/assets/211f72da-20d9-4e53-90c9-4b45e86b1efa)

#### Area report:
![WhatsApp Image 2025-05-20 at 22 09 53_26a070a4](https://github.com/user-attachments/assets/306b020b-1efb-4419-a571-e16290de1f85)

#### Power Report:
![WhatsApp Image 2025-05-20 at 22 09 52_a6b10023](https://github.com/user-attachments/assets/c1f13288-4c3c-4b3f-8904-9e49da2ce2f8)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.

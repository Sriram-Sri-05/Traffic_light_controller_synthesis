# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![WhatsApp Image 2024-11-24 at 22 51 41_787c917e](https://github.com/user-attachments/assets/6b22a231-6d9b-4d7b-8c2b-b6b7147ade63)


Area report:
![WhatsApp Image 2024-11-24 at 22 51 41_e47428b0](https://github.com/user-attachments/assets/0ab0dab0-b612-4cb4-81a5-5ca5a091ef6f)


Power Report:
![WhatsApp Image 2024-11-24 at 22 51 41_4694c7a8](https://github.com/user-attachments/assets/e151c9c2-ce7b-4e41-8315-7af9d7c1c9c4)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.

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

### Synthesis RTL Schematic :

![image](https://github.com/user-attachments/assets/b5ac05c5-a872-474a-ae1b-5be134935943)

### Area report:

![image](https://github.com/user-attachments/assets/0dfd84ae-4666-425b-a4c5-095342cad183)

### Power Report:

![image](https://github.com/user-attachments/assets/3a564f89-f9c5-4267-b69e-9c912aa28efc)

### Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.

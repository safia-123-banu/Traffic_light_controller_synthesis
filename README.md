## Ex No: 06 -Implementation-of-Traffic_light_controller_Synthesis-using-Cadence-EDA-Tools 

### Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

### Tool Required:

- Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)
- Synthesis: Genus


#### Step 1: Getting Started

- Synthesis requires three files as follows,

+ Liberty Files (.lib)
+ Verilog/VHDL Files (.v or .vhdl or .vhd)

#### Step 2 : Creating an SDC File

-	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

#### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

- The Available technology nodes are 180nm ,90nm and 45nm.
- In the terminal, initialise the tools with the following commands if a new terminal is being used.

    + csh
    + source /cadence/install/cshrc

<br>
<br>
<br>
<br>

- The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.
- Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.


#### Synthesis RTL Schematic :

![Screenshot (102)](https://github.com/user-attachments/assets/f6f0fd77-65a3-470a-af29-1370a03f265d)

<br>

#### Area report:

![Screenshot (98)](https://github.com/user-attachments/assets/3c61bb4e-bcc9-4ec3-8e82-13ffd7b9064f)

<br>
<br>

#### Power Report:

![Screenshot (97)](https://github.com/user-attachments/assets/27bdf564-2154-4bd1-a4d7-4dcb1d929ffe)

#### Timing Report:

![Screenshot (95)](https://github.com/user-attachments/assets/93df4e17-4aa3-4913-bc9a-b8b1faf4bbf7)

### Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.

# Traffic_light_controller_Synthesis

**Aim:**

&emsp;&emsp;Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

**Tool Required:**

&emsp;&emsp;Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

&emsp;&emsp;Synthesis: Genus

**Step 1: Getting Started**

&emsp;&emsp;Synthesis requires three files as follows,

&emsp;&emsp;&emsp;&emsp;◦ Liberty Files (.lib)

&emsp;&emsp;&emsp;&emsp;◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

**Step 2 : Creating an SDC File**

&emsp;&emsp;•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

**Step 3 : Performing Synthesis**

&emsp;&emsp;The Liberty files are present in the library path,

&emsp;&emsp;&emsp;&emsp;• The Available technology nodes are 180nm ,90nm and 45nm.

&emsp;&emsp;&emsp;&emsp;• In the terminal, initialise the tools with the following commands if a new terminal is being used.

&emsp;&emsp;&emsp;&emsp;◦ csh

&emsp;&emsp;&emsp;&emsp;◦ source /cadence/install/cshrc

&emsp;&emsp;&emsp;&emsp;• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

&emsp;&emsp;&emsp;&emsp;• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

**Synthesis RTL Schematic :**

![Screenshot 2024-11-13 144942](https://github.com/user-attachments/assets/aa552359-c5f1-4ef2-82e5-f72d1b6244eb)

**Area report:**

![Screenshot 2024-11-16 163430](https://github.com/user-attachments/assets/9ade2121-5ade-42c5-8320-b785d15b57fb)


**Power Report:**

![Screenshot 2024-11-16 163536](https://github.com/user-attachments/assets/9eff52de-a7cc-4488-bb21-2bf0b30dc2f9)

**Result:**

&emsp;&emsp;The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.

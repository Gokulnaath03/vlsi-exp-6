# EXP 6:

# SCHEMATIC AND SIMULATION OF CMOS INVERTOR USING CADENCE VIRTUOSO.

## AIM:
To Schematic and Simulate Invertor  using CADENCE virtuoso.

## APPARATUS REQUIRED:

CADENCE VIRTUOSO.

 ## PROCEDURE:

## Procedure for Commands to get into Cadence
1. Right Click and open the terminal window
2. Type the following commands as follows and press enter.<br>
i) tcsh<br>
ii) source /home/install/cshrc<br>
iii) virtuoso

## Procedure for Schematic simulation using Cadence

1. Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…"<br>
2. Close the 2nd window<br>
3. Use 1st window i.e virtuoso window(CIW) for further processing.<br>
i) Create a New Library<br>
ii) Create Schematic Cell view.<br>
iii) Create the Symbol for schematic Cell view.<br>
iv) Create the test Cell view.<br>
v) Analog simulation by spectre<br>

## Procedure for Creating New Library.

a) File –New – Library<br>
b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library,
Click OK<br>
c) Attach the library to the technology library gpdk045.Click OK

## Create Schematic Cell view.

a) Go to 1st window i.e virtuoso(CIW)<br>
b) File-New-Cell view<br>
c) Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name<br>
Ex: Inverter View: Schematic<br>
d) Type: Schematic press OK<br>
e) Add the required components from the libraries and make the connections.<br>
f) Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on
browse. This opens the library browser ow select the appropriate library for components like
Gpdk045,nmos, pmos<br>
g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin<br>
h) Make the connections by using fixed narrow wire key<br>
i) Click Check and Save button.

## Creating the Symbol for schematic Cell view

a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell
view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok<br>
b. Now Symbol generation form appears. Click Ok If No changes required<br>
c. A new window with with default symbol is created.<br>
d. Edit the symbol if you want to give actual symbol shape else continue.<br>
i. Execute Create-Cell view-from cell view<br>
ii. Library Name and Cell Name must be same which you have used for schematic. Press OK<br>
iii. Check for the position of pin side.Prss OK<br>
iv. Edit for the shape by Create-Shape-Choose required options to edit.

## Creating the new test cell view

a) Go to CIW window, Execute File-New-Cell view<br>
b) Setup the new file form<br>
Library: Select the one you a created.<br>
Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test<br>
View: Schematic<br>
Type: Schematic press OK<br>
Analog simulation by SPECTRE.<br>
a. In test cell view window<br>
b. Launch – ADE L(Analog Design Environment)<br>
c. Execute Setup—Simulation/directory/Host A new window opens<br>
d. Set the simulation window to spectre and click ok<br>
e. Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type<br>
as stat then press OK.<br>
f. Execute Analysis – Choose. A window opens.<br>
g. Select the type and set the specifications and press OK<br>
h. Execute Output s—to be plotted – Select on Schematic<br>
i. Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse<br>
j. Execute Simulation -- Net list and Run

## Simulation Settings

Setup for transient analysis:<br>
1. Stop time = 400n<br>
Setup for D.C analysis<br>
2. Component to be selected in schematic is for d.c analysis<br>
3. Start = -1 Stop = 1 resp.

## CMOS INVERTER:
![image](https://github.com/Gokulnaath03/vlsi-exp-6/assets/167178811/c120c993-b3a6-4b23-87c3-ca4b5be25424)


## OUTPUT:
![image](https://github.com/Gokulnaath03/vlsi-exp-6/assets/167178811/e1b6166b-1ab8-4740-92b9-529e15fee357).


## NANDGATE:
![image](https://github.com/Gokulnaath03/vlsi-exp-6/assets/167178811/c40e87f6-a544-459a-8d32-e6fda558f7be)


## OUTPUT:
![image](https://github.com/Gokulnaath03/vlsi-exp-6/assets/167178811/afcb84c7-458c-4c39-9b99-ac66ff06f51a)


## NORGATE:
![image](https://github.com/Gokulnaath03/vlsi-exp-6/assets/167178811/793328f0-050e-482f-8043-05e79a26a1f7)


## OUTPUT:
![image](https://github.com/Gokulnaath03/vlsi-exp-6/assets/167178811/d84f9fcf-d190-4c86-8e42-4f30037b8967)

## RESULT:
The schematic and simulate inverter using CADENCE is done and verified successfull.




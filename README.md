
# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :  thenmozhi.p
 # REGISTER NUMBER :  212223100059
 # DEPARTMENT :  CSE(cs)
 # YEAR : III

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:

AND

<img width="263" height="266" alt="image" src="https://github.com/user-attachments/assets/2c4d000b-2e33-4699-b45b-7e4cb39f662e" />

OR

<img width="257" height="256" alt="image" src="https://github.com/user-attachments/assets/a8180e65-d9dc-4eb8-bf2d-e71e74569a83" />


NOT

<img width="252" height="164" alt="image" src="https://github.com/user-attachments/assets/a62de7e8-d8e6-4d7d-99b6-e59aeba2f793" />

NAND

<img width="248" height="256" alt="image" src="https://github.com/user-attachments/assets/890bf2d2-08b3-4b18-bd47-b53b1d18cbcd" />



NOR 

<img width="262" height="257" alt="image" src="https://github.com/user-attachments/assets/97511440-4826-42a8-84e2-b6d13e614073" />


XOR


<img width="286" height="265" alt="image" src="https://github.com/user-attachments/assets/f2154dde-e2ff-46f1-b172-23c8e6342def" />


XNOR


<img width="251" height="261" alt="image" src="https://github.com/user-attachments/assets/52ceedd5-9078-4cd4-802b-a264af01902c" />

 
# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 

**AND & OR GATE**

<img width="723" height="757" alt="image" src="https://github.com/user-attachments/assets/4c8e1674-e1a2-48b8-a8cf-139fa3f980ce" />

<img width="763" height="764" alt="image" src="https://github.com/user-attachments/assets/77a3e52c-2e2d-4e99-b664-54e9e27572f1" />

**NOT GATE**

<img width="542" height="302" alt="image" src="https://github.com/user-attachments/assets/afffd14c-6d9a-4b7e-a4c7-7bf99449aae1" />

**NAND GATE**

<img width="585" height="769" alt="image" src="https://github.com/user-attachments/assets/ec98f211-472c-4f5d-a949-2082671d98f3" />
<img width="601" height="263" alt="image" src="https://github.com/user-attachments/assets/4654acd8-ccb6-4c05-b31f-552970b4c3e1" />



**NOR GATE**

<img width="484" height="640" alt="image" src="https://github.com/user-attachments/assets/3accae9b-af26-422a-8d39-4045ffe6ce66" />
<img width="515" height="641" alt="image" src="https://github.com/user-attachments/assets/6c73a1b1-4832-4c67-8c8b-fb2bd75d1185" />



**XOR & XNOR GATES**

<img width="620" height="791" alt="image" src="https://github.com/user-attachments/assets/7c27324e-1665-4385-9b31-1771205ad239" />

<img width="620" height="791" alt="image" src="https://github.com/user-attachments/assets/27be48a3-1e04-44c7-b1c2-97a8a1332acc" />



**Results:**

The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.


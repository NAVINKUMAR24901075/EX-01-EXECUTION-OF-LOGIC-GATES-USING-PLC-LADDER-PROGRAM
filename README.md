# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : NAVINKUMAR.S
 # REGISTER NUMBER : 212224110041
 # DEPARTMENT : CSE-IOT
 # YEAR : III
 # DATE : 26-10-2-26

 
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

## AND Gate:
Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.

## OR Gate:
Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.

## NOT Gate:
Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.

## NAND Gate:
Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.

## NOR Gate:
Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.

## XOR Gate:
Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.

# Truth Tables:
## AND GATE:
<img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/0ff4023b-ca2a-4b80-9fd9-838db40e76ff" />

## OR GATE:
<img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/fd306b8f-c25b-4a78-a640-ec9c952ea425" />

## NOT GATE:
<img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/75941921-97d4-4a16-929c-682f25e993ec" />

## NAND GATE:
<img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/204ab996-7c11-4799-ab30-e5546e1061c0" />

## NOR GATE:
<img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/84ad6f45-9bb0-4be2-80dc-cb327d73cddb" />

## XOR GATE:
<img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/b025d37f-171c-4107-9268-16d7b79537c9" />



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

## AND GATE:

<img width="717" height="136" alt="image" src="https://github.com/user-attachments/assets/bd71aa72-bc61-47ce-b83c-4b7dc7c04643" />

<img width="647" height="146" alt="image" src="https://github.com/user-attachments/assets/d942371c-bd0a-4714-b026-7e766a00b431" />

<img width="682" height="140" alt="image" src="https://github.com/user-attachments/assets/60aac668-a229-4d6f-8bc8-356817b13e21" />

<img width="727" height="157" alt="image" src="https://github.com/user-attachments/assets/945031f4-4ea7-4b92-8f6b-b3994fc0be8f" />


## OR GATE:

<img width="668" height="212" alt="image" src="https://github.com/user-attachments/assets/3f5f1141-ee83-47d1-960e-41959b4c07f8" />

<img width="667" height="215" alt="image" src="https://github.com/user-attachments/assets/6c941137-2653-4cc2-a034-cf8567b6366f" />

<img width="662" height="215" alt="image" src="https://github.com/user-attachments/assets/5c6c0315-7063-41ac-a5dc-f5b800de9e04" />

<img width="681" height="210" alt="image" src="https://github.com/user-attachments/assets/2fbfae06-4602-4719-b056-c7b94679271e" />


## NOT GATE:

<img width="718" height="136" alt="image" src="https://github.com/user-attachments/assets/ec289bda-9a31-4522-84e7-985812171699" />

<img width="677" height="147" alt="image" src="https://github.com/user-attachments/assets/0b3f8e34-9c9d-4a0a-9ce8-c90c1d7e3922" />

<img width="748" height="160" alt="image" src="https://github.com/user-attachments/assets/0ef07798-46a7-4157-8a56-e2a1227f2b66" />

<img width="672" height="142" alt="image" src="https://github.com/user-attachments/assets/756a775f-1381-4c6c-806f-cb4f200a3e3b" />


## NAND GATE:

<img width="710" height="152" alt="image" src="https://github.com/user-attachments/assets/3d8e671a-a299-4257-903a-d40844f9715f" />

<img width="721" height="158" alt="image" src="https://github.com/user-attachments/assets/d29dd5a8-902e-45da-bf80-b2299f923d29" />

<img width="762" height="151" alt="image" src="https://github.com/user-attachments/assets/a4005ae6-d62f-4896-bef0-88b8d8d65f2f" />

<img width="690" height="142" alt="image" src="https://github.com/user-attachments/assets/5640837b-6e98-4f67-ad28-31a8aca247d5" />


## NOR GATE:

<img width="705" height="216" alt="image" src="https://github.com/user-attachments/assets/65b280a3-bfe0-40ca-a9d8-d26bd37f69a0" />

<img width="652" height="237" alt="image" src="https://github.com/user-attachments/assets/e474fa01-b88f-4df7-a6c4-3f10ddaed839" />

<img width="716" height="217" alt="image" src="https://github.com/user-attachments/assets/a224e5b6-2713-4735-9a1b-33fcc1eb546b" />

<img width="662" height="218" alt="image" src="https://github.com/user-attachments/assets/c8650ceb-21e0-4c37-96ed-af5dd383068c" />


## XOR GATE:

<img width="722" height="246" alt="image" src="https://github.com/user-attachments/assets/6929a959-17d0-46d3-b9b3-c1cdd6bae933" />

<img width="698" height="242" alt="image" src="https://github.com/user-attachments/assets/e69b217a-926b-4f56-8082-706e71fb489e" />

<img width="716" height="251" alt="image" src="https://github.com/user-attachments/assets/b4fb9f90-b4a3-468b-8594-3fb3c8202757" />

<img width="708" height="230" alt="image" src="https://github.com/user-attachments/assets/63cb1bf1-15d0-47d5-8437-34fffa169028" />


## MONITOR TABLE:

<img width="1917" height="733" alt="image" src="https://github.com/user-attachments/assets/7678eccd-0090-4be1-a8a2-f8bdc6b5fab9" />

<img width="1917" height="752" alt="image" src="https://github.com/user-attachments/assets/880ef80f-f618-4829-b874-58b6daedb1d7" />

<img width="1917" height="736" alt="image" src="https://github.com/user-attachments/assets/ee295eb2-3d19-4e04-9351-ee2c3669d0ca" />

<img width="1917" height="750" alt="image" src="https://github.com/user-attachments/assets/0e978d1f-45fb-467f-af00-765ea1d11368" />


# Results:

The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.

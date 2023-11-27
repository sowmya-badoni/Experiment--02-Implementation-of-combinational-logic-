# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
Logic gates are electronic circuits which perform logical functions on one or more inputs to
produce one output.
Logic gates are electronic circuits which perform logical functions on one or more inputs to
produce one output. F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D F2=xy’z+x’y’z+w’xy+wx’y+wxy
1.AND gate The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are
high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB Y= A.B
2.OR gate The OR gate is an electronic circuit that gives a high output (1) if one or more of its
inputs are high. A plus (+) is used to show the OR operation. Y= A+B
 

## Procedure:
1.Create a project with required entities.
2.Create a module along with respective file name.
3.Run the respective programs for the given boolean equations.
4.Run the module and get the respective RTL outputs.
5.Create university program(VWF) for getting timing diagram.
6.Give the respective inputs for timing diagram and obtain the results

## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: SOWMYA BADONI
RegisterNumber:  23001999
*/
## CODE
![Exp2codeii](https://github.com/sowmya-badoni/Experiment--02-Implementation-of-combinational-logic-/assets/152136324/4e353e20-9e7e-439a-94a7-b16a10e5fa42)

### F1
![Exp2codei](https://github.com/sowmya-badoni/Experiment--02-Implementation-of-combinational-logic-/assets/152136324/0c7fec25-27ba-4c3c-bd8f-a445ec614fe1)

## RTL:
### F1
![Exp2 f1](https://github.com/sowmya-badoni/Experiment--02-Implementation-of-combinational-logic-/assets/152136324/559731c4-296e-469b-8993-3a8c240ebb09)

###F2
![Exp2 f2](https://github.com/sowmya-badoni/Experiment--02-Implementation-of-combinational-logic-/assets/152136324/5630b79c-75bf-4698-b011-d9c021984422)

## OUTPUT:
## TIMING DIAGRAM:
### F1
![Exp2 f1 timing](https://github.com/sowmya-badoni/Experiment--02-Implementation-of-combinational-logic-/assets/152136324/1480d08d-0aca-4c93-a823-757f9f0b6a91)

### F2:
![Exp2 f2 timing](https://github.com/sowmya-badoni/Experiment--02-Implementation-of-combinational-logic-/assets/152136324/a74d17cb-ae58-4d76-91ba-c5bcba2017fd)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.

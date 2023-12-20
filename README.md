# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin
![image](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/3c084430-a6b0-4230-adba-9796546de57d)



#### Figure -01 HALF ADDER 
![image](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/38bd68bb-2593-4b83-be99-d555bac99063)




#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:SANDHIYA P 

RegisterNumber:23012555  
*/
# HALF ADDER PROGRAM:

![Screenshot (44)](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/75df33a4-8e7c-4c13-9338-5782998126fb)

# HALF ADDER TRUTH TABLE:


![image](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/f945af3d-641c-4678-a33e-41fe7bf59113)


# HALF ADDER RTL VIEW:


![Screenshot (42)](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/51ba484d-dc55-4573-87d3-5b6caebfd199)


# HALF ADDER TIMING DIAGRAM:

![image](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/f7f91a5c-17a6-49f0-b551-11ce3823451b)

# FULL ADDER PROGRAM:

![Screenshot (47)](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/85b8ca04-aa99-4a68-9410-11e2ab087334)


# FULL ADDER TRUTH TABLE:

![image](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/f0815a7d-2530-4d6b-8228-aa4410354de8)

# FULL ADDER RTL VIEW:

![image](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/567260b0-ac3b-4d63-90f8-e487ddc5eb59)




## FULL ADDER RTL VIEW:
![Screenshot (46)](https://github.com/Sandhiyapalanivel/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743091/c9c7473b-4ff4-4a72-a65f-4d9ea85aa0d7)


### Result:

   Thus the given logic functions are implemented using and their operations are verified using verilog programming.

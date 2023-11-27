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
![Screenshot 2023-11-27 202149](https://github.com/MangariDeeraj/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365485/d6518644-5838-4710-994e-79275b5ff5c6)


#### Figure -01 HALF ADDER 


![Screenshot 2023-11-27 202808](https://github.com/MangariDeeraj/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365485/d50b187b-cc31-4a97-a14f-619539351765)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:![Screenshot 2023-11-27 202129](https://github.com/MangariDeeraj/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365485/0024c197-d306-457a-bc44-04ff9190d98b)     

![Screenshot 2023-11-27 202808](https://github.com/MangariDeeraj/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365485/051c958b-fd98-4ca9-a44c-fa7e813c474f)

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: M.Deeraj
RegisterNumber:23000244  
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
### TIMING DIAGRAM
![Screenshot 2023-11-27 202335](https://github.com/MangariDeeraj/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365485/8762232a-9e8d-4fc7-b528-65a98fe83899)

![Screenshot 2023-11-27 203005](https://github.com/MangariDeeraj/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365485/21d25e2f-3afc-4bab-b6db-6406c245ebac)

### TRUTH TABLE 

### Result:

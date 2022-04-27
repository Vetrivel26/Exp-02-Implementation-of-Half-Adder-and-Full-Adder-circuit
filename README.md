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

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: vetrivel.s
RegisterNumber:  212221240060

input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and(y1,a,b);
or(y2,a,b);
not(y3,a);
nand(y4,a,b);
nor(y5,a,b);
endmodule
*/
Logic symbol & Truthtable
RTL realization

### Output:
# HALF ADDER: Logic Symbol & Truth Table:
![01](https://user-images.githubusercontent.com/95363138/165556339-6bfb4f39-909e-4a3c-b1d1-6ca2d3c09c97.png)
# RTL realization:
![02](https://user-images.githubusercontent.com/95363138/165556481-73405857-5eeb-499d-b861-2aa4d613e9d8.png)
# Timing Diagram:
![03](https://user-images.githubusercontent.com/95363138/165556603-42e95cd5-5e30-46fe-a0a0-0d6a7645a127.png)
# FULL ADDER: Logic Symbol & Truth Table:
![04](https://user-images.githubusercontent.com/95363138/165556724-79c3de72-755a-4d6f-84c3-8ac577336d82.png)
# RTL realization:
![05](https://user-images.githubusercontent.com/95363138/165556812-7937c6fe-d267-4029-8848-25cc8db8833b.png)
# Timing Diagram:
![06](https://user-images.githubusercontent.com/95363138/165557003-2e51b121-bc6c-485e-9429-d0ccf1a2d9a5.png)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming

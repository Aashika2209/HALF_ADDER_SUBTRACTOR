# EXP3 : HALF_ADDER_SUBTRACTOR

## Implementation-of-Half-Adder-and-Half Subtractor-circuit
## NAME: AASHIKA JAIN .G
## REF NO. : 24900589

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
![half add TT](https://github.com/user-attachments/assets/5045f085-81cf-42a9-b3c5-68fe1fd8f0d2)
![half sub TT](https://github.com/user-attachments/assets/ba614b84-7db6-4a08-96a4-f6d9a70c6d90)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and half subtractor circuit and verify its truth table in quartus using Verilog programming.
![pro half add](https://github.com/user-attachments/assets/a07339c3-f2ff-4ce1-8346-74bcb8e57929)
![pro half sub](https://github.com/user-attachments/assets/abea49d5-5dba-4929-a598-ec8c8fa7ec9e)



**RTL Schematic**
![rtl of half add](https://github.com/user-attachments/assets/c12cac68-2f86-4e9f-b077-d57226c33d4d)
![rtl of half sub](https://github.com/user-attachments/assets/172a73aa-12d6-4069-acf0-6754c3112489)



**Output/TIMING Waveform**
![output half add](https://github.com/user-attachments/assets/761ecb67-2ef2-46a7-adda-f821e1d43026)
![output half sub](https://github.com/user-attachments/assets/e78dc767-e0a7-4c10-b880-4f1c5e911f86)



**Result:**
Thus half adder and half subtractor is implemented.

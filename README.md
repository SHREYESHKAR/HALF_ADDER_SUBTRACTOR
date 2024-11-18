# NAME : SHREYESHKAR SEKAR
# REFERENCE NUMBER : 24900622
# EXP2 : HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

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

**HALF SUBTRACTOR**
![image](https://github.com/user-attachments/assets/f38519a5-1e9f-4f23-a0fa-e2895783c108)

**HALF ADDER**
![image](https://github.com/user-attachments/assets/fa6d4b6b-380a-4477-a50e-d038c9736ce0)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and half subtracter circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/ 24900622

**RTL Schematic**

**HALF SUBTRACTOR**
![DE HALF SUBTRACTOR DIA](https://github.com/user-attachments/assets/828b84f7-3c02-4458-9028-91221fb1b934)

**HALF ADDER**
![DE HALFADDER DIAGRAM](https://github.com/user-attachments/assets/443f37ed-4f75-4d70-89d3-6797c96fdda3)


**CODING** 

**HALF SUBTRACTOR**
![HALF SUBTRACTOR CODE](https://github.com/user-attachments/assets/2f611368-095b-4b6d-9a48-9cb2b770e6f8)

**HALF ADDER**
![WhatsApp Image 2024-11-18 at 11 43 56 AM](https://github.com/user-attachments/assets/ea254cc4-5771-4a2c-8812-fc677d962c93)


**Output/TIMING Waveform**

**HALF SUBTRACTOR**
![DE HALF SUBTRACTOR OUTPUT](https://github.com/user-attachments/assets/e47129ca-fa96-4592-ae04-68039049dee3)

**HALF ADDER**
![DE HALF ADDER](https://github.com/user-attachments/assets/6fd8d8e9-6451-4268-9cd1-2fedc4f4db02)

**Result:**

**HALF SUBTRACTOR**
![DE HALF SUBTRACTOR OUTPUT](https://github.com/user-attachments/assets/a9064f8a-7218-4834-a505-774d9ff63d33)

**HALF ADDER**
![DE HALF ADDER](https://github.com/user-attachments/assets/de6a5eec-9bf2-4fe8-a2cc-1c04d001f0bf)


Thus a half adder and half subtractor circuit is designed and the truth table is verified in Quartus using Verilog programming.

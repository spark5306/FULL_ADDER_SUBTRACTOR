# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

![image](https://github.com/user-attachments/assets/c3417f9b-4346-4a31-a144-e81a0064a5e8)


**Procedure**

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram.
6. 
**Program:**

![image](https://github.com/user-attachments/assets/7f8bf5fb-c50d-4055-8431-20fc09563e22)

![image](https://github.com/user-attachments/assets/bf853421-2fee-4530-8306-31ae15dde840)


Developed by: Sarukesh D

RegisterNumber:212224050044


**RTL Schematic**

![image](https://github.com/user-attachments/assets/8153ed96-fe0e-4d4d-86d7-67a223f46aac)


**Output Timing Waveform**

![image](https://github.com/user-attachments/assets/6321fca7-ed60-437e-980a-3aded8053492)

![image](https://github.com/user-attachments/assets/d0c26dfc-81a6-4e14-ba99-7307921c7098)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is 
verified using Quartus software.





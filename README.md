# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
![de3](https://github.com/user-attachments/assets/929b8878-5e59-49b8-8edc-2eca2b981a12)


Developed by:SHAABIN R S RegisterNumber:*/24006663


**RTL realization**
![de4](https://github.com/user-attachments/assets/886fb96a-84a6-4e3c-befe-f338685d1a83)

**Output:**

**RTL**

**Timing Diagram** a b c d ~b ~d ~a ~c (~b & ~d) (~a & b & d) (a & b & ~c) f1 (final result) 0 0 0 0 1
 1 1 1 1 0 0 1 0 0 0 1 1 0 1 1 0 0 0 0 0 0 1 0 1 1 1 0 1 0 0 1 0 0 1 1 1 0 1 0 0 0 0 0 0 1 0 0 0 1 1 1 0 0 1
 1 0 1 0 1 0 0 1 1 0 1 0 1 0 1 1 0 0 1 1 0 0 0 0 0 0 1 1 1 0 0 1 0 0 1 0 1 1 0 0 0 1 1 0 1 1 0 0 1 1 0 0 1 1
 0 0 1 0 0 0 0 1 0 1 0 1 1 0 0 1 0 0 1 1 0 1 1 1 0 0 0 0 0 0 0 1 1 0 0 0 1 0 1 0 1 1 1 1 1 0 1 0 0 0 1 0 1 0
1 1 1 1 0 0 1 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 1 0 1

![de5](https://github.com/user-attachments/assets/a2147486-d8b8-4585-b8e0-1924ae00ea6e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


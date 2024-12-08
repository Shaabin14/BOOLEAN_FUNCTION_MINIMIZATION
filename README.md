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
 ![de2](https://github.com/user-attachments/assets/12e4790f-6a58-4c9c-897b-d7a3b570d393)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
![de3](https://github.com/user-attachments/assets/eb6b9ebc-88a6-4dd2-a5b9-bda5fe5e4d6c)


Developed by:SHAABIN R S RegisterNumber:*/24006663


**RTL realization**
![de4](https://github.com/user-attachments/assets/b184297a-2408-4471-8348-3e6b1325db7b)

**Output:**

**RTL**

**Timing Diagram**a b c d ~b ~d ~a ~c (~b & ~d) (~a & b & d) (a & b & ~c) f1 (final result) 0 0 0 0 1
 1 1 1 1 0 0 1 0 0 0 1 1 0 1 1 0 0 0 0 0 0 1 0 1 1 1 0 1 0 0 1 0 0 1 1 1 0 1 0 0 0 0 0 0 1 0 0 0 1 1 1 0 0 1
 1 0 1 0 1 0 0 1 1 0 1 0 1 0 1 1 0 0 1 1 0 0 0 0 0 0 1 1 1 0 0 1 0 0 1 0 1 1 0 0 0 1 1 0 1 1 0 0 1 1 0 0 1 1
 0 0 1 0 0 0 0 1 0 1 0 1 1 0 0 1 0 0 1 1 0 1 1 1 0 0 0 0 0 0 0 1 1 0 0 0 1 0 1 0 1 1 1 1 1 0 1 0 0 0 1 0 1 0
1 1 1 1 0 0 1 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 1 0 1
![de5](https://github.com/user-attachments/assets/a4b4051d-12c4-4f9a-a833-2c7cdba27d21)

**Result:**
 Thus the given logic functions are implemented using and their operations are verified using
 Verilog programming
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


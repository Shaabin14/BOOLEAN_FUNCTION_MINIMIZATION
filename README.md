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


 ![de18](https://github.com/user-attachments/assets/5642dfc1-152b-4238-9a14-4c0f91cc1b56)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by:SHAABIN R S RegisterNumber:*/24006663


 module experiment2(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule


 
 module experiment2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y & z)|( w & y )|(x & y))
 endmodule

**RTL realization**



![de19](https://github.com/user-attachments/assets/e3066543-b288-42a0-a5e4-f89581154877)






![de20](https://github.com/user-attachments/assets/ec122850-e926-4b35-9785-fa01a9e9173a)


**Output:**



![de21](https://github.com/user-attachments/assets/14e50194-f028-4cfb-bf64-525ccded9da6)




K-MAP



![de22](https://github.com/user-attachments/assets/e98fc4e8-86a2-4124-8cd0-4246f5b77195)




![de23](https://github.com/user-attachments/assets/3f8999cd-e578-4dcc-bf38-d401fd41c954)



**Result:**
 Thus the given logic functions are implemented using and their operations are verified using
 Verilog programming



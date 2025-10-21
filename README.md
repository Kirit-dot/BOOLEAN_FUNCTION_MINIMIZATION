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

module ex_2(a,b,c,d,w,x,y,z,f1,f2) intput a,b,c,d,w,x,y,z; output f1,f2; assign f1=((~b&~d)|(~a&b&d)|(a&b&~c)); assign f2=((~y&z)|(x&y)|(w&y)); endmodule

Developed by: RegisterNumber:*/

215015046


**RTL realization**

<img width="1183" height="615" alt="{77F655A2-B29D-4A9C-83CA-D0FFEC86A040}" src="https://github.com/user-attachments/assets/6c4cf9cd-b2a2-4966-84b8-2d79f07acaf1" />


**Output:**

**RTL**

**Timing Diagram**

<img width="1164" height="346" alt="image" src="https://github.com/user-attachments/assets/ab69df46-dadf-440a-943d-6b7ed9106578" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


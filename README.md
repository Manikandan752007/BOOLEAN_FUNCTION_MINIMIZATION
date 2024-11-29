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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~ b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

Developed by: RegisterNumber:24900527


**RTL realization**
![image](https://github.com/user-attachments/assets/f7be4304-eefc-429f-b232-e10fbad69bd3)

**Output:**

**RTL**

**Timing Diagram**
![Screenshot 2024-10-22 113234](https://github.com/user-attachments/assets/2ed8efe7-1318-4f81-8bec-f73a1fa1390d)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


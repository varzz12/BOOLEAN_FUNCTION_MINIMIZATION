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

module experiment2(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

module experiment2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: VARUNA R RegisterNumber: 212225040483 */


**RTL realization**

<img width="1042" height="563" alt="Screenshot 2026-05-31 142103" src="https://github.com/user-attachments/assets/b8f476d5-5853-4acd-9cf6-ba10d20c56c2" />


**Output:**

**RTL**
<img width="1040" height="678" alt="Screenshot 2026-05-31 142111" src="https://github.com/user-attachments/assets/50595f3d-83d0-449e-b408-a14caf6907e8" />


**Timing Diagram**

<img width="1044" height="620" alt="Screenshot 2026-05-31 142125" src="https://github.com/user-attachments/assets/9036ec62-c4ff-4b51-8ce4-8729ee7bb1f8" />
<img width="1044" height="616" alt="Screenshot 2026-05-31 142136" src="https://github.com/user-attachments/assets/539d8c3e-bcd8-4677-8665-ac2760d89080" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


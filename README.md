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
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule



Developed by:Rougith D RegisterNumber:25017014


**RTL realization**

![exp22](https://github.com/user-attachments/assets/f8949d5c-d49a-4882-aa59-0e392d3249dc)
![exp21](https://github.com/user-attachments/assets/87f2e2bd-8a6c-4455-acdb-f9a1bd6293a1)


**Output:**
<img width="1564" height="796" alt="Screenshot 2025-12-04 212152" src="https://github.com/user-attachments/assets/73a058d8-d430-429b-a8b3-af36eb113f4c" />
<img width="1475" height="698" alt="Screenshot 2025-12-04 192034" src="https://github.com/user-attachments/assets/78d45aa5-8ff6-4603-8310-a64c476611ff" />




**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


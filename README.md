# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
F1
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

F2
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```


Developed by:Madhushri
RegisterNumber:*/24005365


**RTL**
F1
![image](https://github.com/user-attachments/assets/65a3441f-aa34-4432-9f40-e7577f91c340)

F2
![image](https://github.com/user-attachments/assets/11e8a638-19eb-4b0d-9697-74ba922271b2)

**Output:**
F1 output
![image](https://github.com/user-attachments/assets/a8f2ee3a-571d-4988-a65c-8c32e5cb6bf3)

F2 output

![image](https://github.com/user-attachments/assets/e14acff1-5d2b-40b6-9b28-eab7f5838ad3)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


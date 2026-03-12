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
```
module de2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~b&~d | a&b&~c | ~a&b&d;
assign f2 = ~y&z | x&y | w&y;
endmodule
```
```
Developed by: A.Allahbakash 
RegisterNumber:212225240007
```

**RTL realization**

<img width="760" height="660" alt="Screenshot 2026-03-10 090804" src="https://github.com/user-attachments/assets/2214ff12-d4c8-415b-b585-1b7e823430f0" />

**RTL**
<img width="1904" height="978" alt="Screenshot 2026-03-10 090745" src="https://github.com/user-attachments/assets/6758165d-9f14-4851-9a78-6eea7d25e0e2" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


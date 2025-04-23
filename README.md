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

Developed by: RegisterNumber: 212224230219
```
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module exp22(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**Output:**

**RTL**
![image](https://github.com/user-attachments/assets/010bf6ca-00ed-4250-b62c-eb103ef1af46)

![image](https://github.com/user-attachments/assets/9191b265-e794-47ca-b384-0d329d61cb02)

**Timing Diagram**
![image](https://github.com/user-attachments/assets/8e3dcbf2-7cdd-4ac2-b1b6-02dcb15a4461)
![image](https://github.com/user-attachments/assets/c5e366a4-36db-4552-b492-0f5ca4ea9196)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


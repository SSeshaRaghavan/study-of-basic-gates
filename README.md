### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: S Sesha Raghavan
 RegisterNumber: 24900320
 
**Logic symbol & Truthtable**
![WhatsApp Image 2024-12-02 at 14 28 20_07414ab0](https://github.com/user-attachments/assets/6f3ea816-7739-45ac-9a8f-3de390941f19)
![Screenshot 2024-12-07 102753](https://github.com/user-attachments/assets/f1e2d37b-b75a-4d6a-9834-be2660f8ba38)


**RTL realization Output:** 
![WhatsApp Image 2024-12-02 at 14 28 20_04d86fc0](https://github.com/user-attachments/assets/18098561-922d-46f1-a335-0ad32f6f411c)

**RTL**
![Quartus II 64-Bit - C__altera_13 0sp1_basic_gates - basic_gates 07-12-2024 10_20_22 AM](https://github.com/user-attachments/assets/638f86f2-a3a4-48f8-bd78-18d1c4994006)

**Result:**
![Quartus II 64-Bit - C__altera_13 0sp1_basic_gates - basic_gates 07-12-2024 10_51_45 AM](https://github.com/user-attachments/assets/5233a438-2049-4bad-a79f-3a78701ea20d)



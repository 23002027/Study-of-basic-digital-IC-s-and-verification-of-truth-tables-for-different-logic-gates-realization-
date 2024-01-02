# Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-
 AIM:
To study about the different digital IC’s and to verify the truth table in Quartus for the basic logic gates using Verilog programming.

## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
## THEORY
## Introduction:
Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate
OR gate
NOT gate
NAND gate
NOR gate
Ex-OR gate
Ex-NOR gate
1) AND gate
The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB

Y= A.B

2) OR gate
The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.

Y= A+B

3) NOT gate
The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.

Y= A'

4) NAND gate
This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.

Y= (AB)’

5) NOR gate
This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.

Y= (A+B)’

6) Ex-OR gate
The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.

Y= A⊕B

7) Ex-NOR gate
The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.

Y= A⊕B

Procedure
## (i) Connect the supply (+5V) to the circuit.
## (ii) Switch ON the main switch.
## (iii) Press the switches for inputs “A” and “B”. The switch is ON state when 1 is pressed. The switch is OFF state when 0 is pressed.
## (iv) If the output is 1, then the bulb glows.
## (v) Check all the gates following the same procedure.
## Program:
Program to verify the truth table in quartus for the basic logic gates using Verilog programming.
## Developed by: KAMESH RR
## RegisterNumber: 223002027
``````
module ex01(A,B,Y1,Y2,Y3,Y4,Y5,Y6,Y7);
input A,B;
output Y1,Y2,Y3,Y4,Y5,Y6,Y7;
and (Y1,A,B);
or (Y2,A,B);
not (Y3,A);
xor (Y4,A,B);
xnor (Y5,A,B);
nand (Y6,A,B);
nor (Y7,A,B);
endmodule
``````
OUTPUT:
Logic symbol & Truthtable
![Screenshot 2024-01-02 194829](https://github.com/23002027/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139752981/cc21d528-5e4b-4bb8-9808-a3dc3fa2c671)
![Screenshot 2024-01-02 194913](https://github.com/23002027/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139752981/026d13d0-d56c-414e-a69f-c0e0636e386c)
![Screenshot 2024-01-02 194947](https://github.com/23002027/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139752981/61d5addf-e333-42d1-ab38-f6cd891b3ef5)
![Screenshot 2024-01-02 195038](https://github.com/23002027/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139752981/6d34c216-b954-4dcc-84b4-ea87f13b184e)

RTL realization
![Screenshot 2024-01-02 195119](https://github.com/23002027/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139752981/2dcd1844-1266-433f-86e3-4bb74a5b7380)
WAVEFORM:
![Screenshot 2024-01-02 195157](https://github.com/23002027/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139752981/84c2aecf-dc54-4eae-b648-0799a7a03de5)




Result:
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.

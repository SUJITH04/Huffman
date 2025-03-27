### EXP NO : 7 HUFFMAN CODING
### AIM:
To implement Huffman coding schemes using SCILAB.
### PROGRAM:
Huffman Coding
clear all;
clc;
//given
P_x1 = .05//probability of first signal
P_x2 = .15//probability of second signal
P_x3 = .2//probability of third signal
P_x4 = .05//probability of fourth signal
P_x5 = .15//probability of fifth signal
P_x6 = .3//probability of sixth signal
P_x7 = .1//probability of seventh signal
n1 = 4//number of bits in code obtained from table given textbook
n2 = 3//number of bits in code obtained from table given textbook
n3 = 2//number of bits in code obtained from table given textbook
n4 = 4//number of bits in code obtained from table given textbook
n5 = 3//number of bits in code obtained from table given textbook
n6 = 2//number of bits in code obtained from table given textbook
n7 = 3//number of bits in code obtained from table given textbook
//calculations
I_x1 = -log2(P_x1);
I_x2 = -log2(P_x2);
I_x3 = -log2(P_x3);
I_x4 = -log2(P_x4);
I_x5 = -log2(P_x5);
I_x6 = -log2(P_x6);
I_x7 = -log2(P_x7);
H_x = P_x1*I_x1 + P_x2*I_x2 + P_x3*I_x3 + P_x4*I_x4 + P_x5*I_x5 + P_x6*I_x6 + 
P_x7*I_x7;//entropy
L = P_x1*n1 + P_x2*n2 + P_x3*n3 + P_x4*n4 + P_x5*n5 + P_x6*n6 + P_x7*n7;
neta = (H_x*100)/L//Efficiency in percentage
//results
printf("\n\nEfficiency in percentage = %.2f percent",neta);
### OUTPUT
P_x1 = 0.05 
P_x2 = 0.15 
P_x3 = 0.2 
P_x4 = 0.05 
P_x5 = 0.15 
P_x6 = 0.3 
P_x7 = 0.1 
n1 = 4. 
n2 = 3. 
n3 = 2. 
n4 = 4. 
n5 = 3. 
n6 = 2. 
n7 = 3. 
neta = 98.882715 
Efficiency in percentage = 98.88 percent
### RESULT:
Thus Huffman coding are performed using SCILAB

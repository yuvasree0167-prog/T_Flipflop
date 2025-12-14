# T_Flipflop
AIM:

To implement T flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

T Flip-Flop

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.
<img width="584" height="355" alt="Screenshot 2025-12-14 215609" src="https://github.com/user-attachments/assets/b7db9435-c1af-4170-9c92-8e968cf1e5a3" />



This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

<img width="453" height="336" alt="Screenshot 2025-12-14 215621" src="https://github.com/user-attachments/assets/36a658fa-7a8e-4812-9aaa-7e73795e50c5" />


From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

Procedure

PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:YUVASREE S RegisterNumber:25014102 */

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS:Thus the T flipflop using verilog and validating their functionality using their functional tables is implemented and verified.

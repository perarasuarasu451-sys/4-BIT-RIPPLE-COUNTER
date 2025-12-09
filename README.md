# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.
<img width="555" height="707" alt="image" src="https://github.com/user-attachments/assets/e027266e-176a-4572-a662-c8b088819ace" />

 Developed by: PERARASU K RegisterNumber:25004665


**RTL LOGIC FOR 4 Bit Ripple Counter**
<img width="617" height="783" alt="image" src="https://github.com/user-attachments/assets/f190d652-d356-4f13-b447-81442b2190b1" />

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
<img width="1312" height="323" alt="image" src="https://github.com/user-attachments/assets/26448f88-cc62-4703-ba3b-6df8f622ad60" />

**RESULTS**
Thus 4-BIT-RIPPLE-COUNTER is verified successfully.

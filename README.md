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

1.Code Overview: Understand the Verilog module ripple_counter, which includes clock (clk) and reset (rst) inputs, and a 4-bit output count. The counter increments on each positive clock edge unless reset is asserted, resetting the count to 0.

2.Simulation Preparation: Use a Verilog simulator (e.g., ModelSim) and write a testbench module to apply clock and reset signals while monitoring the counter output.

3.Testbench Implementation: Instantiate the ripple_counter module in the testbench, generate clock and reset signals, apply them to the counter module, and observe the count output.

4.Simulation Execution: Compile both the counter module and the testbench, simulate the design, and verify that the counter counts from 0 to 15 (binary 1111) and resets to 0 when the reset signal is activated.

5.Verification and Debugging: Analyze timing diagrams to ensure proper counter behavior, debug any encountered issues during simulation, and make necessary modifications to the design for optimal functionality.

**PROGRAM**

**Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.**

 **Developed by: sidharthan V**
 
 **RegisterNumber:212223050049**
 
![330493553-de75b5a7-8cf6-4f5a-978a-46cf59bdf177](https://github.com/monish1545/4-BIT-RIPPLE-COUNTER/assets/166646660/7e7905ba-e913-4643-9d3d-7bf152eec4bd)


**RTL LOGIC FOR 4 Bit Ripple Counter**

![330493596-e8a9f0f9-1217-4e48-a364-3c4551f4f567](https://github.com/monish1545/4-BIT-RIPPLE-COUNTER/assets/166646660/6d11db0a-734f-4a5c-a498-02f44906975e)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![330493656-855631ba-ee38-4d53-834c-e35d513cf2f8](https://github.com/monish1545/4-BIT-RIPPLE-COUNTER/assets/166646660/9cab009d-7f06-4877-93ae-16dc744ee912)

**RESULTS**

Thus, program excueted successfully

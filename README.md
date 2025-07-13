1. Arithmetic Logic Unit (ALU)
An ALU is a critical component of any processor, responsible for performing arithmetic and logical operations. A basic ALU supports functions such as addition, subtraction, AND, OR, and NOT. It takes two 4-bit inputs and uses a control signal to select the operation. The output reflects the result along with a zero flag to indicate if the result is zero.

2. RAM Design
Synchronous RAM allows read and write operations triggered on the clock edge. A simple design includes a 4-bit address line to access 16 memory locations, each 8 bits wide. The we signal controls write operations, and data is always available on the output for reads.

3. Pipelined Processor Design
A 4-stage pipelined processor breaks execution into Instruction Fetch (IF), Instruction Decode (ID), Execute (EX), and Write Back (WB) stages. This increases throughput by processing multiple instructions in parallel. Basic instructions include ADD, SUB, and LOAD.

4. Digital FIR Filter Design
A Finite Impulse Response (FIR) filter processes digital signals using a fixed number of coefficients. A simple 4-tap FIR filter computes a weighted sum of the current and past three input samples. It is implemented using shift registers and multipliers, with coefficients stored in the design.

# -single-cycle-processor-design-
single-cycle processor design in which each instruction complete in one clock cycle and each instruction are 12 bit long:3 bit for opcode and 9 bits for operands 
 single-cycle processor design in which each instruction complete in one clock cycle and each instruction are **12 bit long:3 bit for opcode and 9 bits for operands** 
The processor has the following registers 
*	A program counter(PC)
*	Instruction Register(IR)
*	I/O buffer Register(IBR)
*	Two general-purpose registers, A and B
*	at the rising edge, instruction is fetched from instruction memory and stored in instruction register(IR) .during the HIGH level of the clock signal PC  is incremented by 1, the instruction is decoded and necessary control signals are generated. ALU operations (instruction fetch, instruction decode, fetch operands, execute)  are also performed.
*	Destination operands are written at the falling edge of the CLK signal 
*	The CPU is connected to separate instruction and data memories 
*connected to the CPU through IBR
To complete this project in the given timeline l break down the task in manageable units and list out all possible risks that might stop us from reaching those milestones, first build 4-bit ALU and expand it to 16 and then build the datapath for the processor which includes all the registers, data and instruction memories, ALU, multiplexers and so on before constructing the control unit we simulated the execution of instructions by manually providing the required control signals to make sure the datapath is correct
***
finally build a simple assembler using java that translates the assembly like instructions (mnemonics ) into machine codes(hexadecimal).there was some issue like a bidirectional bus between data memory and the general-purpose registers to mitigate this l used a tri-state buffers, two data sources for PC and the general-purpose register to mitigate this l suggested using multiplexers ***for more info u can lookup readme doc file***

## 1.2 The Central Proccesing Unit - Hardware Components

#### Q: What does the CPU interact with?
- A: *The CPU interacts with the main memory to perform proccessing in a computer*

#### Q: What are the 3 main components that make up a CPU? 
- 1. *The Control Unit: which cordinates the proccesing steps*
- 2. *The Register: is a small storage unit for within the CPU. Registers are also the smallest and fastest cache's in a computers architecture*
- 3. *Arithmetic/Logic Unit: performs calculations and makes decsions*


#### Task: Draw figure 1.13 and describe what it is depeciting?
- A: *Figure 1.13 is a diagram of the main components which make up a CPU the Arithemtic/Logic Unit, Control Unit, and Registers. Which are all connected via the Bus and which is connnected with the Main Memory*


#### Q: What is the relationship of the main memory and the CPU and the control unit?
- A: *The control unit is actually coordinating the transfer of data instructions from main memory into the registers of the CPU*
- A: *The control unit also coordinates the execution of the circutry in the arithmetic/logic unit to prefom operations on the data that is stored in the pariualar registers*


#### Q: What are some examples of a register being reserved for specific purposes?
- A: *A specific register reserved for a specific purpose is an "Instruction Register" which holds the current instruction being executed*
- A: *Another example is the "Program Counter" which is a register that holds the address of the next instruction to be executed*


#### Q: Explain the innovation in Jon von Nuemann computer architecture?
- A: *Storing both the program instructions and data togther in main memory*
- A: *Thus the computer is capable of follow the "Fetch-Decode-Execute Cycle"*

#### Q: What are the steps of the 5 steps of the Fetch-Decode-Execute-Cycle?
- 1. *Instructions are fetched form main memory at the address stored in the progam counter*
- 2. *The instructions are put into the instructions regitser*
- 3. *The program counter is then incremented at this point to prepare for the next cycle*
- 4. *The instruction is decoded electronnically to determine which operation to carry out*
- 5. *Finally the control unit activates the correct circuitry to carry out the instuctions, which may load a data value into the register or add two values*


#### Task: Draw figure 1.14 and describe what is occuring?
- A: *The figure is depcting the continous loop that occures between the main memory, and CPU's main components. Which is the instruction comming form the main memory over to the register, the control unit processing what to do with the instructions and the executing the instructions*


### Key Concept: What is the cycle that froms the foundation computer processing?
- A: *The Fetch-Decode-Execute Cycle*


#### Q: What is the chip that the CPU is constructed on, that is a device that is a part of the main circuit board of the computer?
- A: *The CPU is constructed on a chip called the "microprocessor", a device that is apart of the computers main circuit board*
- A: *Furthermore this board also conatins ROM chips and communicates sockets to which device controllers, such as the controller that manages the video display, can be connected*


#### Q: What is the "System Clock" and why is it crucial to the main circuit board?
- A: *The system clock synchronizes the events of the CPU by generating electronic pulses in regular intervals*
- A: *Clock speed is a rough estimate of how fast a CPU excutes for example the Intel Dual Core i7 Processor runs at a clock speed of 3.1 GHz, approximately 3.1 billion pulses a second*



#### Q: What are the specification of a dual-core processor, and what are the limitations of software when interacting with the second processor?
- A: *A dual-core processor is actually has two processors built into one chip, and can do two things at once if the program is executing is designed for such a thing.*

- A: *It difficult to write programs that leverage both processors. But this will become increasingly easier due to future processor design; likely to be more cores, and not single cores that run faster speeds*
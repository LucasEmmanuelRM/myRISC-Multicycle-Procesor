# myRISC-Multicycle-Procesor
myRISC is a educational processor based in the MIPS architecture. It has a reduced number of supported instructions (R, I and J instructions) with each one being a 4 bytes word. There are 32 registers in myRISC.

This is a multicycle version of myRISC, also called myRISC v2, which follows the Harvard Architecture. The following instructions are supported: LW and SW, R-Type, BEQ, ADDI and J. The hardware components are managed by a finite state machine acting as a control unit.

![Finite State Machine](https://github.com/user-attachments/assets/607a9c83-b0c5-4f1c-b0ab-ff51ffd76790)

The processor can be simulated via EdaPlayground. This project was assigned as part of the Computer Organization and Architecture course assessment, led by Professor Max Santana Rolemberg Farias at the Federal University of Vale do São Francisco. The datapath and finite state machine diagram was provided by the professor.

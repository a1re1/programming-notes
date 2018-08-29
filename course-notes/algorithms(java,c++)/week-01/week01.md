# Outline

Components of a computer:
  - CPU
    - Control Unit <-> Data Path
    
    | CU Uses | DP Uses |
    |---------|---------|
    | gives instructions to data path; what to do, when to do it, what data to work with | moves, stores, and manipulates user data |

  - Memory
  - Input
  - Output

Machine Language(ML) is a binary language used by the hardware to run programs
  - Syntax
  - Vocabulary
    - opcode: tell you task to work with
    - operands: data that you are working with
    - every opcode has an assignment; thus equal is generally not an operand

  - Encoding: how lines are interpreted
  - Instruction set architecture; ISA

MIPS:
|opcode|operand|operand|operand|code|opcode|
|---|---|---|---|---|---|
|opcode|source1|source2|dest|code|opcode|

  - Uses a fixed length encoding; 32 bits
  - Some languages use variable length encoding

Assembly Language:
  - every one line of machine code is translated to one line of machine code
  - mnemonic: is a the way in which assembly represents machine code with readable translations
  - pseudo instructions will generate multiple lines of machine code like a macro
  - Most compilers will output machine code instead of assembly

ISA:
CISC |------------------------------------------------------| RISC
Complex instruction set computer| reduced instruction set computer

CISC:
  - some instructions do a lot of work
  - VAX is a CISC computer
  - x86 is CISC computer

RISC:
  - Reduction in complexity
  - all instructions do the smallest amount of work
  - Does not necessarily mean less instructions
  - MIPS is a RISC language
  - PowerPC is RISC similar but has more operating instructions than x86

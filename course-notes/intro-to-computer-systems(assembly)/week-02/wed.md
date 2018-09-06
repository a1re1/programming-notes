## MIPS - R2000
  - load/store Machine (only load and store instructions can access memory)
  - all other instructions have registers
  - 32 32-bit registers are given in manipulates
  - $0...$31
  - all instructions must fit on one line
  - [label:][opcode[operands][,operand]...][#comment]
    - cannot be over 80 char in length
    - [label:] symbolic representation of characters that represents a memory location, translated by assembler (like #DEFINE in C) (can only use a label once)
    - opcode - operation code
    - operands - what the opcodes are working on
    - #comment
### Standards
  - coding standard (must not go over 80 char line length)
  - no indentation to represent scope
  - labels must be on left-hand margin, **cannot have code on a line with a label**
  - all opcodes must be lined up after an 8-space tab
  - all comments will be lined-up with white space

### MIPS
  - LOAD and STORE are the only two instructions that can manipulate memory
  - ALU (Arithmetic and Logic Unit) Instructions in MIPS
  - All binary operations will take 3 operations
   - rd = rs (op) rt [ie: c = a + b]
   - add rd,rs,rt # rd = rs + rt
   - add $8,$8,$4
  - Pseudo-instructions:
    - Unary Operations: not rd,rs #bitwise inversion: nand rd,rd
    - Generally we cannot use pseudo instructions in this class (We can use 7)
      - 1) not
      - 2)
      - 3)
      - 4)
      - 5)
      - 6)
      - 7)
  - ALU - Immediate Instructions
    - Uses 1 short signed const inside the instruction itself
    - rt = rs (op) immediate
    - addi rt, rs, imm # add with an immediate

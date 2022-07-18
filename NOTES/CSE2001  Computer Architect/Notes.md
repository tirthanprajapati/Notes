- Main goal of Computer architecture is to design and develop high perfimabce computers
# Computer Functions
- Data processing
- Data storage
- Data movement
- Control

# Memory unit
-> Primary memory
    -> RAM
    -> ROM
-> Secondary memory
	-> HDD
	-> SSD


# Memory Types
- RAM ( Ramadom Acess Memory )
   For user
- ROM ( Read Only Memory )
   It as pre installed codes provided by the hardware provider and it has booting codes( helpes the pc to boot ( Bootstrap ) )
- EPROM, PROM, EEPROM


# Instruction register(IR)
-> Holds the ionstrutions that is currently in use and being excecuted . Its outputr is 
     available for the control 9circuits which generates the timing signals that control the various processing elements in one execution of instruction
-> Three things in IR
	->Operand
	->Operator
	->Result Address


# fetching
Lets suppose secondary storage has a world in it, then bring the world from secondary storage to RAM is called fetching

if data is brought to CPU then it is acalled fetching

# MBR( Memory Buffer Register )
# MAR( Memory Address register )
# MDR ( Memory Data register )
- If memory is given to MDR that means data has been fetched.
# AC ( Accumilator )
# PC ( Program Counter )
# CIR ( Current Instruction Register )
# Operating Steps
- programs reside in the memory & usually get this info througj I/P unit.
- Execution of the program starts when the PC is set to the point of the first instructions of the progeram 
- contentrs of PC are transferred to MAR and a Read COntrol Signal is sent to the memory
- After the time required toa cess the memory elapses,the adderss word spread out of the memory and Loaded into the MDR
- MDR to IR and then codes are ready to decoe and execute
- if the instrctions involves an opeartion by the ALU , it is necessary to require the necessary oprands
- an opearnd is feached ny sending its address to MAR and initaiating a read cycle
- when opearand has been read by the memory, it is sent from MDR to ALU
- after 1/2 opearations ALU can perform necessary opeations


![[Pasted image 20220629094417.png]]


# 01/06/22

- ## *Von Neumann-based computer*
-> every thing is stored in a single memory
-> onlyone bus is available
-> simultanious operations are not much possible
-> not so effecient as compared to haward design of computers


# Types of Buses
- Address Bus
- Data Bus
- Control Bus

# Addessing Modes





# *Types of Addressing Modes*
- Effective Addressing Mode
- Implied Addressing Mode.
- Immediate Addressing Mode
- Register Addressing Mode
- Register Indirect Addressing Mode
- Auto-increment or Auto-decrement AddressingMode
- Direct Addressing Mode
- Indirect Addressing Mode
- Displacement Address Addressing Mode
- Relative Addressing Mode
- Index Addressing Mode
- Stack Addressing Mode


# *Instruction Cycle*
2 Types
-> Fetch Cycle
-> Execute Cycle

if both are combined called Fetch-Decode-Execute cycle.

**STEPS**
-> Instruction fetch
-> Instruction format and decoding
-> after getting data location the data is been fetched
-> Data Fetch 
-> then opeartion is done on operand
-> if there are intermediate solutions they are stores uin ACCUMILATOR
**-> When ever an instruction is completed Program Counter increases by 1+**


# Importanat Links
- https://www.geeksforgeeks.org/harvard-architecture/
- https://www.geeksforgeeks.org/computer-organization-von-neumann-architecture/

# Introduction to ISA ( Instruction set architecture )
![[Pasted image 20220701091102 1.png]]

- ISA helps software and hardware interact with each other
- it is an intermediate which helps hardware and software interact with each other.
- Instrutions are different for different architecture
- Instruction set is a boundarty where computer designer and the computer programmer see the same computer in different ways just like blind people describing an elephant.
- Instruction is represented in bits.
- the layput of instruction is called an instructions format
- These instructions are machine dependent. ie for the same operation different computer have different instructions.
- **MIPS** ( million instruction per second )
## Instruction format
- the length
- the type
- length and position of operation codes
- number and length of operand address

## elements of instruction
- what operation to perform
- on what opearmnds

# Hypothetical Instruction Format
** Image **

/* mode 
operand 
opcode* */

# Instruction set design consideratiuon
- data type
- operations
- instruction formats
- set of techniques for addressing data
- no. of registers that can be refferd

# Operand data type
** image **

# type of instructions
- Data transfer instruction
	- Transfer of Data
- Data processing Instructions
	- operations are perfomed
	- Deals with ALU
- Program control
	- 
- miscellaneous/Privilleged

** images **


# Language Processing Activities

 **ALL this process are done during compailation**
-> program generation activities
-> program execution activities


(     APPLICATION       *Program generation*           ( PL                   *Program execution*              
     DOMAIN        )    ----------------------->         Domain )    ------------------------->


##  Program Generation
*  Images  *
## Program Execution
*  Images  *

## Program Translation
* Images *

-> Machine language is also called target program
High leve Language --->  Translator Program --->  Assembly Language




# # in c is use for pre processing or called gateway]




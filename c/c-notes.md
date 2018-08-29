# C Basics
## Variables and Data Types:
C is statically typed; types are known at compile time
C is also weakly typed; types can be changed using typecasting
Types can be misused

## Basic Scalar types:
|type	|description	|size|
|int	|Integers	|4 bytes*|
|float	|floating point	|4 bytes|
|double	|floating point	|8 bytes|
|char	|ascii char	|1 byte|
|bool	|c99 added 1bit boolean	|4 bytes|
|void*	|address	|4/8 bytes|
*depends on architecture 64bit vs 32bit

Type specifiers:
	- There is a tradeoff between representational capacity of a variable and the memory requirement
	- Three axes:
		○ size, sign, scope

|type	|min size|
|short int |2 byte|
|int	|4 bytes*
|long int	|8 bytes
|long double	|8/16 bytes*|

8 bits = 1 byte
an 8-bit integer type has 256 possible combinations bitwise
integer types have a signed bit by default

Control flow:
	- if statements
	- switch statements
	- ternary statements
	- goto statements

The only false value in C is 0; NULL is also zero; false

Switch statements operate in O(1) time and allow fall through

IO is buffered by enter character in C

CTRL-C kill program	CTRL-D EOF (End of File) symbol

Ternary operator
(<condition>)?(<if-true>):(<if-false>)

Goto
labal:
goto label;

C has a sizeof operator to find out size of types for a system

User defined types; and defined types are extra types in C:
	ex:
		- size_t x = sizeof(int)
		- print with %zu

The size of a pointer depends on the architecture
	64-bit uses 8 bytes; 32-bit uses 4 bytes

static -- makes global vars private to a file, and makes local variables persist across calls
const -- promise to compiler that value will not change

Switch statements will goto code to execute then proceed to run everything afterwards; end code block with break statement

Iteration is normal:
	for loops;
	while loops;
	do {<statements>} while (<condition>);

	continue -- skip rest of iteration and go to next cycle
	break -- get out of loop

echo {input} | {program}	simulate sending input by piping into the program

look up any C function with: man {function}

Arrays
	- Arrays are composite data types
	- elements of an array are contiguous in memory
	- an array variable contains the address of the first element
	- cannot be returned from functions
cannot be resized

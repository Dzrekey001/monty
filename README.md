**Monty - A Monty ByteCode Interpreter**
***
Monty is an interpreter for Monty ByteCode files. Monty ByteCode files contain instructions that manipulate a unique stack. This project aims to implement various operations on the stack, such as push, pop, swap, add, subtract, multiply, divide, modulus, print, and more.

1. Table of Contents
2. Installation
3. Usage
4. File Format
5. Supported Operations
6. Examples
7. Contributing

***
Installation
To compile and run the Monty interpreter, follow these steps:

Clone the project repository:
```shell
$ git clone https://github.com/your-username/monty.git
```

Navigate to the project directory:
```shell
$ cd monty
```

Compile the source code using gcc:
```shell
$ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
```

***
**Usage**
To run the Monty interpreter, execute the following command:
```shell
$ ./monty file
```
where file is the path to the Monty ByteCode file you want to interpret.
****
File Format
Monty ByteCode files typically have the .m extension. Each line in the file represents an instruction or command to be executed by the interpreter. Instructions consist of an opcode followed by an optional argument.

Example:

```
perl
push 42
pall
```
***
**Supported Operations**

The Monty interpreter supports the following operations:

1. push <int>: Pushes an integer onto the stack.
2. pall: Prints all the values on the stack.
3. pint: Prints the value at the top of the stack.
4. pop: Removes the top element of the stack.
5. swap: Swaps the top two elements of the stack.
6. add: Adds the top two elements of the stack.
7. nop: Does nothing.
8. sub: Subtracts the top element from the second top element of the stack.
9. div: Divides the second top element by the top element of the stack.
10. mul: Multiplies the second top element with the top element of the stack.
11. mod: Computes the rest of the division of the second top element by the top element of the stack.
12. comments: Ignores the line as a comment.
13. pchar: Prints the character corresponding to the ascii value at the top of the stack.

***
**Contributing**

Contributions to Monty are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

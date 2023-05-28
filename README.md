# Monty Bytecode

Monty Bytecode is a simple programming language created for the "Monty 0.98q" project at Holberton School. The purpose of Monty Bytecode is to teach students the fundamentals of bytecode interpretation and stack/queue algorithms. It employs a stack-based approach and utilizes a set of bytecodes or instructions to operate on a stack of integers.

## How it Works

The Monty bytecode interpreter reads a file that contains a sequence of bytecodes and executes them one by one. Each bytecode consists of a mnemonic (a word) followed by an argument. The mnemonic specifies the operation to be performed, and the argument provides any additional information required for the operation.

For example, consider the following Monty bytecode program:

```
push 123
pall
```

In this program, the `push` bytecode is used to push the number 123 onto the top of the stack, and `pall` is used to print all the elements in the stack.

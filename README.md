# push_swap

## Project Overview

`push_swap` is an algorithmic project designed to sort a list of integers using a limited set of stack operations. The objective is to sort the initial data, provided in stack A, into ascending order while using the minimal number of operations. The project uses two stacks, A and B, and a variety of commands (such as push, swap, rotate, and reverse rotate) to accomplish the sorting. This project is commonly used to develop skills in algorithms and data structures, especially for optimizing operation efficiency.

## Usage

### Compilation

Make sure you have a C compiler (for example, `gcc`) installed. To compile the project, simply run:

```bash
make
```

An executable file named `push_swap` will be created in the project directory.

### Execution

To run the program, provide a sequence of non-repeating integers as arguments:

```bash
./push_swap 3 2 5 1 4
```

- The program will output a series of instructions (such as `sa`, `pb`, `ra`, etc.) representing the operations needed to sort the numbers.
- All input values must be integers and must not repeat.

### Supported Commands

- `sa`: swap the first two elements of stack A
- `sb`: swap the first two elements of stack B
- `ss`: execute `sa` and `sb` simultaneously
- `pa`: push the top element of stack B to stack A
- `pb`: push the top element of stack A to stack B
- `ra`: rotate stack A upwards (first element becomes last)
- `rb`: rotate stack B upwards
- `rr`: execute `ra` and `rb` simultaneously
- `rra`: reverse rotate stack A (last element becomes first)
- `rrb`: reverse rotate stack B
- `rrr`: execute `rra` and `rrb` simultaneously

## Notes

- Make sure your input consists of non-repeating integers.
- It is recommended to use a checker program to verify the correctness of the push_swap output.
- For more details about the algorithm implementation, refer to the source code and documentation.

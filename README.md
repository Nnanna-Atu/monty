Introduction,
This is a group project for the Monty language interpreter, focused on implementing stacks and queues using C. The project is part of a learning experience to deepen understanding of algorithms, data structures, and programming in C.

Team Members,
- David Bolorunduro
- Nnanna Atu

Project Overview,

Learning Objectives,
Understand the concepts of LIFO and FIFO.
Grasp the implementation of stacks and queues in C.
Gain knowledge of common use cases and implementations of stacks and queues.
Learn the proper usage of global variables in C.
Comprehend how to share variables between source files using extern.
Adhere to coding standards and best practices.

Project Timeline,
Project Start: December 12, 2023, 6:00 AM
Project Deadline: December 15, 2023, 6:00 AM
Checker Release: December 13, 2023, 12:00 AM

Project Requirements,

General Guidelines,
Allowed Editors: vi, vim, emacs
Compilation: Ubuntu 20.04 LTS using gcc, with specific options (-Wall -Werror -Wextra -pedantic -std=c89)
Code should follow the Betty style, checked using betty-style.pl and betty-doc.pl
Maximum of one global variable is allowed
No more than 5 functions per file
Use of C standard library is allowed
Prototypes of functions should be included in the header file (monty.h)
Use include guards in header files
Repository should follow specific naming guidelines

Data Structures,
Use the following data structures:

struct stack_s - doubly linked list representation of a stack (or queue)
int n: integer
struct stack_s *prev: points to the previous element of the stack (or queue)
struct stack_s *next: points to the next element of the stack (or queue)

struct instruction_s - opcode and its function
char *opcode: the opcode
void (*f)(stack_t **stack, unsigned int line_number): function to handle the opcode

Compilation & Output,
Compile code using:

$ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty

Output should be printed on stdout, and any error messages on stderr.

Monty Language,
Monty 0.98 is a scripting language compiled into Monty byte codes. Files usually have a .m extension. Follow specific rules for file structure.

Usage,
$ ./monty file

If no file or more than one argument is given, print "USAGE: monty file" and exit with status EXIT_FAILURE.
If unable to open the file, print "Error: Can't open file <file>" and exit with status EXIT_FAILURE.
If an invalid instruction is encountered, print "L<line_number>: unknown instruction <opcode>" and exit with status EXIT_FAILURE.
If unable to allocate memory (malloc fails), print "Error: malloc failed" and exit with status EXIT_FAILURE.

Recommendations,
Work collaboratively on a set of tests.
Follow the project tasks in the specified order.
Make use of the provided data structures.

Additional Resources,

Google,
How do I use extern to share variables between source files in C?
Stacks and Queues in C
Stack operations
Queue operations

Copyright & Plagiarism,
Solutions for tasks should be developed independently.
Plagiarism is strictly forbidden and will result in removal from the program.


 # Monty Interpreter

  A language interpreter made in the C programming language to manage stacks a    nd queues (LIFO and FIFO). The aim is to interpret Monty bytecodes files. [Monty](http://montyscoconut.github.io/) is a language that aims to close the     gap between scripting and programming languages.

  ## Requirements
  
   * Allowed editors: vi, vim, emacs
   * All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=c90
  * All your files should end with a new line
  * A README.md file, at the root of the folder of the project is mandatory
  * Your code should use the Betty style. It will be checked using betty-style    .pl and betty-doc.pl
  * You allowed to use a maximum of one global variable
  * No more than 5 functions per file
  * You are allowed to use the C standard library
  * The prototypes of all your functions should be included in your header file called monty.h

* Don’t forget to push your header file
 * All your header files should be include guarded
 * You are expected to do the tasks in the order shown in the project
 
  ## Compilation
 
 To compile this project, you can use the following command:
 ```
 $ make
 ```

 ## Allowable opcodes and what they do

* |opcode  |  functionality|
* | --- | --- |
* |push | add element to the 'top' of stack and 'end' of queue  |
* |pop  | remove element from 'top' of stack and 'end' of queue |
* |pall  |print every member of the structure|

* | pint | prints the member value at the top of stack |
* | swap | swaps the order  of the 1st and 2nd elements in stack |
* | add | add top two member values |
* | sub | subtract the top element from the 2nd top element |
* | div | divide the 2nd element by the top element |
* | mul | multiply the top two elements of the stack |
* | mod | the remainder when the 2nd element is divided by the top element |
* | comment | there is the ability to parse comments found in bytecode ->'#'|
* | pchar | print character at the top of the stack |
* | pstr | print the character at the top of the stack|
* | rotl | moves element at the top to the bottom of the stack |
* | rotr | the bottom of the stack becomes the top |
* | queue, stack | toggles the doubly link list implementation style |
* | nop | opcode should do nothing |

 ## Exit Status
 Exits with status `EXIT_FAILURE`

 ## Compilation
 All files were compiled on Ubuntu 14.04 LTS.

 All programs and functions were compiled with `gcc 4.8.4` using flags `-Wall     -Werror -Wextra and -pedantic`.

 ## Styling
All files have been written in the Betty Style.

 ## Mandatory Tasks
* Task 0: Implement the push and pall opcodes
* Task 1: Implement the pint opcode (The opcode pint prints the value at the top of the stack, followed by a new line.)
* Task 2: Implement the pop opcode. (The opcode pop removes the top element of the stack)
* Task 3: Implement the swap opcode. (The opcode swap swaps the top two elements of the stack.)
* Task 4: Implement the add opcode. (The opcode adds the top two elements of the stack.)
* Task 6: Implement the nop opcode.(The opcode nop doesn’t do anything.)

## Author
**Amarachi Omereife**

## Collaborator
**Anwulika Mordi (anwulika-1)**


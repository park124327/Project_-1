L9 : Specify 'MAX_LEN_LINE' as a constant of 100
L13 : 100 size character array definition
L14 : Enter NULL in memory address
L15 : Type that stores process numbers
L23 : Gets string from stream (stdin : pointer to standard input)
L24-27: If the s address contains nothing, it marks the error with stderr as "fork failed". ('exit(1)' : error message termination, c program itself completely terminated, forced termination)
L29 : len is defined as the length of the character stream
L30 : String Output
L31-33 : Insert \0 defining the end of a string if the last string is \n.
L35 : Output value at command
L37 : Processor Creation
L38-41 : If the processor is not generated, output "fork failed" and exit with an error message.
L42-51 : When it is a parent process, cpid checks whether the pid function has terminated -> output "waitpid failed" if not -> output "Child process terminated" immediately -> output "Exit status is" after checking if the child has terminated normally (TURE)
L52-57 : When a processor is created and is not a parent processor (=child process), the execve function executes another program and outputs "execve failed" if it fails to execute.

<h1 align="center">
  0x16. C - Simple Shell
</h1>

<p align="center">
   📄 🚀
</p>

<p align="center">
  <strong>
   Description
  </strong>
</p>

<p align="center">
This project is a practice of what as been taught in the first sprint at ALX Africa Software Engineering. </br>
The gates of shell is a project that marks the end of the first sprint (c programming), that us (students at alx) understand what happens under the hood of the shell. it enables us to practice system calls, process of functions, bit manipulaton, error handling of files and functions and not forgeting file management</br>
Shell is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh). </br>
This project was written entirely using the C Language.
</p>
  This shell project was built and tested on  Ubuntu 14.04 LTS.

## what our shell does:
* Display a prompt ($) and wait for the user to type a command for it to execute. A command line always ends with a new line.
* If an executable for the command entered cannot be found,  the shell prints an error message and display the prompt again.
* Handle errors.
* Handling the (Ctrl+D) which is the end of file condition
* Handling the command line with arguments.
* Handles the PATH
* Support the exit feature and the exit status
* Handle the Ctrl-C to not terminate the shell
* Handling the command seperator `;`
* Handling `&&` and `||` logical operators
* Handle variable replacements `$?` and `$$`
* Handle the comments `#`
* Support the history feature
* Support the file input

## handling builtin commands
Our shell has support for the following built-in commands:

env - printing te environment
exit - exiting the shell 
alias[name[='value]] - reads alias names
setenv [var][value] - sets an environment variable and valuewhich gets updated when the variable exists.
 unsetenv [var] - removes an environment variable
 help [built-in] - reads the documentation for built ins




|


 ## Installation : Getting HSH
 
Clone the below repository and compile the files into an executable using the GCC compiler.
```
https://github.com/charlespaul1/simpleshell.git
```

### Basic usage: 
compile using this: gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

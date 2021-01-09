# CPL
Computer Programing Language

### Terminology:
- Python, Java, C++, PHP, Ruby, Basic, Perl, JavaScript, and many more are high-level language intended to be relatively straightforward for humans to read and write and for computers to read and process.
- The actual hardware inside the Central Processing Unit (CPU) does not understand any of these high-level languages.
- The CPU understands a language we call __machine language__. Machine language is very simple and tiresome to write because it is represented all in zeros and ones: "001010001110100100101010000001111". So we build various translators to allow programmers to write in high-level languages and these translators convert the programs to machine language for actual execution by the CPU.
- Since machine language is tied to the computer hardware, machine language is __not portable__ across different types of hardware. Programs written in high-level languages can be moved between different computers by using a different interpreter on the new machine or recompiling the code to create a machine language version of the program for the new machine.
- These programming language translators fall into two general categories: (1) interpreters and (2) compilers.
- It is not easy to read or write machine language, so it is nice that we have interpreters and compilers that allow us to write in high-level languages.

### Interpreter
- An interpreter reads the source code of the program as written by the programmer, parses the source code, and interprets the instructions on the fly.
- It is the nature of an interpreter to be able to have an interactive conversation.

### Compiler
- A compiler needs to be handed the entire program in a file, and then it runs a process to translate the high-level source code into machine language and then the compiler puts the resulting machine language into a file for later execution.
- If you have a Windows system, often these executable machine language programs have a suffix of “.exe” or “.dll” which stand for “executable” and “dynamic link library” respectively.
- In Linux and Macintosh, there is no suffix that uniquely marks a file as executable.
- If you were to open an executable file in a text editor, it would look completely crazy and be unreadable:
```
^?ELF^A^A^A^@^@^@^@^@^@^@^@^@^B^@^C^@^A^@^@^@\xa0\x82
^D^H4^@^@^@\x90^]^@^@^@^@^@^@4^@ ^@^G^@(^@$^@!^@^F^@
^@^@4^@^@^@4\x80^D^H4\x80^D^H\xe0^@^@^@\xe0^@^@^@^E
^@^@^@^D^@^@^@^C^@^@^@^T^A^@^@^T\x81^D^H^T\x81^D^H^S
^@^@^@^S^@^@^@^D^@^@^@^A^@^@^@^A\^D^HQVhT\x83^D^H\xe8
....
```
### Writing a program
- When we want to write a program, we use a text editor to write the Python instructions into a file, which is called a __script__.

### What is a program?
- The definition of a program at its most basic is "a sequence of statements that have been crafted to do something".
    It might be easiest to understand what a program is, by thinking about a problem that a program might be built to solve, and then looking at a program that would solve that problem.

### List of programming languages by type
  Click [here](https://en.wikipedia.org/wiki/List_of_programming_languages_by_type) to know about them.
  
### List of text editors
  Click [here](https://en.wikipedia.org/wiki/List_of_text_editors) to know about them.
  Some frequently used text editors:
	1. Visual Studio Code
	2. Sublime Text
	3. Notepad++
	4. Atom

## The building blocks of programs
```
There are some low-level conceptual patterns that we use to construct programs.
These are part of every programming language from machine language up to the high-level languages.
```
__input__ Get data from the “outside world”. This might be reading data from a file, or even some kind of sensor like a microphone or GPS. In our initial programs, our input will come from the user typing data on the keyboard.
__output__ Display the results of the program on a screen or store them in a file or perhaps write them to a device like a speaker to play music or speak text.
__sequential__ execution Perform statements one after another in the order they are encountered in the script.
__conditional__ execution Check for certain conditions and then execute or skip a sequence of statements.
__repeated execution__ Perform some set of statements repeatedly, usually with some variation.
__reuse__ Write a set of instructions once and give them a name and then reuse those instructions as needed throughout your program.

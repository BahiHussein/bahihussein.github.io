---
layout: post
title: Hello World (C programming)
---

## Welcome to C (an advice that you don't have to read)
Working with C programming could be overwhelming for beginners. and that is because C is a low level programming language that requires a good understanding for the way that computers work, process and store data. I would personally recommend that you start with 
1. ruby
2. Javascript 
3. C 

## Hello World C

```
#include <stdio.h>
main(){
    printf("Hello World \n");
}

```

Easy, Right!!. lets go through the few lines that we have wrote to see what is going on this small program. 

***NOTE***
Because you are a beginner, you may will have to understand some coding fundamental (which we will mention below), before writing more code. Building the basics slowly and patiently will help you grow fast. 


+ a C program starts with the #include statement and a name of a file <stdio.h>
    + <stdio.h> is a header file ends with (.h)
+ the '#' is called hash character
+ '#include' is an instruction to the preprocessor to go and look for a file named 'stdio.h' (a header file) and using '<' '>' characters is for looking in a certain search path. In this case the '<' + 'filename.h' + '>' is asking the preprocessor to look for the 'stdio.h' file among the standard system files (Don't worry if you didn't understand. It is easy and will be much clearer soon).
    + The preprocessor is a tool that process your code before sending it to the compilers
    + the compiler is a tool that compiles the file.
    Compiling is a process in which a program is converted from the language that you used to write the program to a machine-code that is understandable by the computer(machine)


>A header file is a file containing C declarations and macro definitions (see Macros) to be shared between several source files. You request the use of a header file in your program by including it, with the C preprocessing directive ' #include '. source [https://gcc.gnu.org/onlinedocs/cpp/Header-Files.html]

In short, header files according to their types, provide different functionalities and capabilities to your program. 

***NOTE***
You don't have to understand the purpose or/and the functionality of header files at this moment. You will understand it later and it will be much much easier when you create you own header file. Take a break. 






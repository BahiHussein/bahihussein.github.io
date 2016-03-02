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

//==> this code will print out "Hello World"

Easy, Right!!. lets go through the few lines that we have wrote to see what is going on this small program. 

***NOTE***
Because you are a beginner, you may will have to understand some coding fundamental (which we will mention below), before writing more code. Building the basics slowly and patiently will help you grow fast. 

### Include and Header Files

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

### The Main() Function 
Do you see this ```main()``` the 'main()' is a function that will be the first thing that  your computer reads when executing your code. So, you program should be inside the the '{}' that follows the 'main()'.
```
main(){
    //your code goes here.
}

```

The '{' and '}' are called curly brackets. the '{' marks the start of the function and the '}' marks the end of the function. And, if you are wondering, what a function is, a function is a a wrapper for some code that you may use more than once. for instance, in real life, you may put all your car cleaning tools in one box. And, whenever you want to clean your car, all what you have to do, is to take that box and use its tools. A function is exactly the same a container for a code that can be used at anytime to make your live easier. 

>A function is a type of procedure or routine. Some programming languages make a distinction between a function, which returns a value, and a procedure, which performs some operation but does not return a value. Most programming languages come with a prewritten set of functions that are kept in a library. [source]:http://www.webopedia.com/TERM/F/function.html

### printing "Hello World"
for now just be sure to know that writing printf("ANYTHING") will printout whatever between the double quotes "". 

```

printf("Hello World \n");
printf("Hello World \n");
printf("Hello World \n");

```
> printout 
> Hello World
> Hello World
> Hello World

the "\n" is called a new line character using which, you ask the computer to move to the next line. Why would i want to move to the next line?!! execute the following code. 

```
printf("Hello World");
printf("Hello World");
printf("Hello World");
```
> this will printout 
> Hello WorldHello WorldHello World

moving to the next line is simply made by adding "\n" at the end of whatever you are trying to print. The "\n" is a called 'a new line character'

### The Evil ';' simicolon character
A simicolon is a character that marks the end of a sentence (Command) in a program. Like any language, your sentence should has a beginning and an end. The program needs to find the simicolon at the end of your command to understand that you already asked for what you want and his turn now, is to execute and serve your command. Why is it EVIL? well, if C is your first programming language, you will feel the pain of forgetting this little character in your first few programs. C programs will not run if you have missing simicolons, so, if you have a problem with your code, always remember to check your simicolons and never feel upset for forgetting it a lot. As a beginner, it is normal to forget simicolons and that should make you laugh.

### Task 1
learning a programming language isn't like learning anything else. Understanding is not enough and the more you code and fail the greater you will be. Here is your first step to greatness. 

> Write a program that prints your name, age and your country. 

That is it. simple, yet vicious. 

I made mine, and it shows the following output. Take a look.

>Name: Bahi Hussein
>Age: 24
>Country: Egypt

You can mail me your tasks on bahi.hussein@gmail.com. It me take up to a week to be able to replay, but i would love to see your first program. 


GoodLuck 


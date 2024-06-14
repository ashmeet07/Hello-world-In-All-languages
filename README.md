markdown

# Hello-world Program In All Languages

##############################################################################################################################
C++
```cpp
// Hello world program in C++

// header file
#include<iostream>
using namespace std;

int main() // main function
{
    cout << "Hello world!"; // output statement
    return 0; // exit statement
}

##############################################################################################################################
C

c

// Hello world program in C

// header file
#include<stdio.h>

int main() // main function
{
    printf("Hello world!"); // output statement
    return 0; // exit statement
}

##############################################################################################################################
Python

python

# Hello world program in Python

print("Hello world!") # output statement

##############################################################################################################################
ArnoldC

vbnet

ITS SHOWTIME
TALK TO THE HAND "hello world!"
YOU HAVE BEEN TERMINATED

##############################################################################################################################
C#

csharp

// Hello World! program in C#
namespace HelloWorld
{
    class Hello {         
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hello World!");
        }
    }
}

##############################################################################################################################
Java

java

// Hello world in Java
class Helloworld {
    public static void main(String[] arg) {
        System.out.println("Hello world!");
    }
}

##############################################################################################################################
Swift

swift

// Hello world in Swift
print("Hello, World!")

##############################################################################################################################
JavaScript

javascript

// Hello world program in JavaScript
document.write('Hello, World!');
alert("Hello world!");
console.log("Hello world!");

##############################################################################################################################
HTML

html

<html>
    <head>
        <title>First Web Page</title>
    </head>
    <body>
        Hello World!
    </body>
</html>

##############################################################################################################################
R

r

# Hello world in R
print("hello world!")

##############################################################################################################################
PHP

php

<?php
   echo "hello world!";
?>

##############################################################################################################################
Perl

perl

#!/usr/bin/perl

# Modules used
use strict;
use warnings;

# Print function
print("Hello World\n");

##############################################################################################################################
Assembly Language (NASM)

asm

global _start

section .text

_start:
    mov rax, 1        ; write(
    mov rdi, 1        ;   STDOUT_FILENO,
    mov rsi, msg      ;   "Hello, world!\n",
    mov rdx, msglen   ;   sizeof("Hello, world!\n")
    syscall           ; );

    mov rax, 60       ; exit(
    mov rdi, 0        ;   EXIT_SUCCESS
    syscall           ; );

section .rodata
    msg: db "Hello, world!", 10
    msglen: equ $ - msg

##############################################################################################################################
Rust

rust

// This is the main function.
fn main() {
    // Statements here are executed when the compiled binary is called.

    // Print text to the console.
    println!("Hello World!");
}

##############################################################################################################################
Kotlin

kotlin

// Hello World Program
fun main(args: Array<String>) {
    println("Hello, World!")
}

##############################################################################################################################
Go

go

package main
import "fmt"

func main() {
    fmt.Println("hello world")
}

##############################################################################################################################
Ruby

ruby

# Hello world in Ruby
puts "Hello World"

##############################################################################################################################
Thank You

Regards,
Ashmeet Singh!

javascript


Feel free to save this as a `README.md` file.
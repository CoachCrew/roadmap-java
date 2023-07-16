---
sidebar_position: 2
---

# S01 - Introduction

<img src={require('@site/static/img/car.vs.computer.jpg').default} />

## Introduction

**Computers are like cars.** They share a lot of similarities 
despite being different in their shapes.
Like cars, computers are constantly in motion, and they are
always running instructions. As cars rely on their engine
to move, Computers rely on Central Processing Unit 
(CPU) to execute instructions and perform tasks. 

**Operating system is the driver**. 
The operating system i.e. Windows, Linux, MacOS, acting 
as the conductor, assumes the role of a person controlling the car.
It manages various components, allocating resources, and ensuring smooth 
functionality, much like how a driver manipulates the car's controls 
to navigate the roads. 

**How does the operating system get control over computer?**
When the computer is powered on or restarted, a process called boot 
happens. During the process, the computer's hardware components, 
including the CPU, undergo initialization. The BIOS or UEFI firmware 
locates the OS stored in the computer's storage device. 
The OS is then loaded into memory, enabling it to establish a 
connection with the CPU. Through this connection, the OS gains 
control over the CPU, allowing it to execute instructions, manage 
resources, and coordinate the overall operation of the computer. 

**What language does the computer speak?**
Computers operate using a binary system, where information 
is represented using only zeros and ones. However, 
the interpretation of these zeros and ones depends on 
the specific architecture of the computer's CPU, 
such as ARM64 or X86. Each architecture assigns unique meanings 
to the binary values. This is accomplished through a set 
of instructions known as the Instruction Set Architecture (ISA), 
which establishes a mapping between instructions and their 
corresponding binary representations.

## Writing the first program
In this session, we write a program that prints `Hello world!`
to the console.

1. Create a directory called `hello` using the following command.
```bash
$ mkdir hello
```

2. Create a file called `main.c` using the following command.
```bash
$ touch main.c
```

3. Edit `main.c` and write the following program in `main.c`.
```c
#include <stdio.h>

int main() {
  printf("%s\n", "Hello world!");
  return 0;
}
```

4. Compile the program using the following command.
```bash
$ gcc main.c -o main
```

5. Run the program. 
```bash
$ ./main
Hello world!
```
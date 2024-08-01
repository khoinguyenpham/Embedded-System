# Embedded-System

## <ins>Description</ins>:

In this project, I  will create a build system using the GNU tools, GCC and GNU Make. To be more specific, compile multiple files, link them together and create a final output executable. We will need to support two platforms; the host environment and the target embedded system MSP432. While the host system will allow you to simulate software on a host platform, the target system will be used in upcoming assignments as we begin to create our microcontroller applications.

Subsequently, I write more C-programming code, and integrate this code with my build system. I will reuse your version control repository and add some new c-programming functions that manipulate memory. I will test your code on my host machine. 

## <ins>Eplaination</ins>:

You will see 2 directories and a file:

1. msp432p401r.lds - The linker file you are to use for linking

2. ‘src’ folder : contains five source files (*.c)

-Makefile - The makefile you are to edit for the assignment

-sources.mk - The source file you are to edit for the assignment

-main.c - Main file you are to work with

-memory.c - File that interacts with memory through an IO abstraction interface

-interrupts_msp432p401r_gcc.c - MSP432 specific C-file for interrupts

-startup_msp432p401r_gcc.c - MSP432 specific C-file for startup

-system_msp432p401r.c - MSP432 specific C-file for for system information

3. ‘include’ folder : contains the three directories of supporting header files

-common - Contains common headers for both platform targets

-msp432 - Contains MSP432 platform headers

-CMSIS - Contains ARM architecture specific headers

*** Inside the common folder, you have been provided a memory.h and a platform.h file. The platform.h file gives you an interface to printf using the macro PRINTF as a mechanism to reduce the dependencies on the stdio.h library.

You need to support two target platforms and their own specific compilers. These two platforms are the HOST and the MSP432. The host embedded system will use the native compiler, gcc. The target embedded system will use the cross compiler, arm-none-eabi-gcc. 

## <ins>Implemention</ins>:

![image](https://github.com/user-attachments/assets/a0ae713c-b77f-48da-af10-bc122caac0ad)

![image](https://github.com/user-attachments/assets/652e3052-e7ee-4bdd-b7d6-a2a2bfa415f3)

![image](https://github.com/user-attachments/assets/8c250b23-9a90-4c7d-8460-bd735c934d7b)

![image](https://github.com/user-attachments/assets/a6db8529-87ff-4f25-8d05-3a6627f9c681)

![image](https://github.com/user-attachments/assets/10a0c04a-9aea-4af7-8771-6c3802601fa6)

![image](https://github.com/user-attachments/assets/6fe5ca17-ea39-4c83-828d-dd143a65b85b)

![image](https://github.com/user-attachments/assets/75e2c96c-a943-43f3-b28b-f731a174dbc2)

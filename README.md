MSP430 LaunchPad Study
======================

## Environment

* Mac OSX Mountain Lion
* Macports
* mspgcc

Install

    % sudo port install msp430-gcc msp430-gdb msp430-libc mspdebug


## Develop

edit "main.c".

    % make

=> compile "main.elf"

    % mspdebug rf2500
    (mspdebug) prog main.elf
    (mspdebug) run

run program on MSP430 LaunchPad.

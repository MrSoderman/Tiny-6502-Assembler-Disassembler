# Tiny 6502 Assembler/Disassembler

A tiny and minimal assembler and disassembler for the 6502 microprocessor, written in JavaScript.
It simply converts 6502 mnemonics into machine code and vice versa.
Right now, it's somewhere between a machine code monitor and a fully fledged assembler.
It's designed for educational purposes, experimenting, retro computing enthusiasts, and small projects involving 6502-based systems.
 
## Features

- Assemble 6502 assembly code into binary machine code
- Disassemble 6502 machine code into readable assembly
- Supports the standard 6502 instruction set
- Supports labels
- Supports comments
- Lightweight and easy to use
- Written in pure JavaScript, no external dependencies

> ⚠️ **Work in Progress:** This project is under active development and may contain bugs or incomplete features. Use with caution and feel free to contribute improvements or bug fixes.

## Known Issues

- Labels are not yet supported in branch instructions (e.g., `BEQ label`)
- Indirect jumps using labels (e.g., `JMP (label)`) are not currently handled

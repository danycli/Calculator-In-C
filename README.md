# Basic Calculator in C

A simple yet stylish **console-based calculator** written in C. It evaluates basic arithmetic expressions (`+`, `-`, `*`, `/`) and presents results in a visually engaging way using **UTF-8 box characters** and **ANSI colors**.

---

## Features

-  **Basic Operations**: Supports `+`, `-`, `*`, `/`
-  **Multi-digit Integers**: Handles multi-digit numbers (e.g., `122 + 321`)
-  **Whitespace Tolerant**: Ignores unnecessary spaces
-  **Division by Zero Detection**: Graceful error message for zero division
-  **Console UI**: 
  - Uses box-drawing characters: `╔`, `║`, `═`, `╝`, etc.
  - Color-coded output using ANSI escape codes
- **Loop Mode**: Continue solving multiple expressions until user exits
- **Modular UI Functions**: Clean code for result, error, success boxes

---

## Preview

<img width="1119" height="629" alt="image" src="https://github.com/user-attachments/assets/f84c5d98-c80d-475a-9cb6-3c5d872a2509" />


## Future Plans
The project is built with scalability in mind. Here are upcoming features:

 -Parentheses support for operator precedence

 -Improved parsing using the Shunting Yard Algorithm

 -Better error handling for invalid expressions

 -Code modularization for better readability

 -Optional GUI version in the future

## Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/C-STD%20C99-00599C?logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/GCC-Compiler-4EAA25?logo=gnu&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows%20Terminal-CLI-4D4D4D?logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/UTF--8%20(chcp%2065001)-Encoding-000000" />
  <img src="https://img.shields.io/badge/ANSI%20Colors-Console%20Styling-FF4C00" />
  <img src="https://img.shields.io/badge/Standard%20Library-stdio.h%20%7C%20string.h%20%7C%20ctype.h%20%7C%20stdlib.h-6E6E6E" />
</p>

### Breakdown

| Component            | Why it’s used                                         |
|---------------------|--------------------------------------------------------|
| **C (C99)**         | Core language for performance & full control           |
| **GCC / MinGW**     | Easy, cross-platform compilation                       |
| **Windows Terminal**| Better Unicode + color rendering                       |
| **UTF‑8 (chcp 65001)** | Proper display of box-drawing characters              |
| **ANSI Escape Codes** | Clean success/error/result styling in the console     |
| **Standard Library**| Input parsing, string ops, classification, memory utils|



## Author
Danial Ahmed (DANY)

# Employee-Record-System-using-C-programming
A very basic project on Employee Record System using C Programming built as my first semester project.
# Employee Record System (C Project)

This is a basic **Employee Record Management System** written in C, developed as a first semester project. It uses file handling to store and manage simple employee records such as name, age, and basic salary.

## Features

-  Add employee records  
-  View/list all records  
-  Modify existing records  
-  Delete records  
-  Stores data in a binary file (`EMP.DAT`)

## How It Works

The program uses a `struct` to represent each employee and stores their data in a binary file. The menu-driven interface allows users to perform different operations like adding, modifying, listing, or deleting employees.

All records are stored persistently in `EMP.DAT`, and temporary changes are written using a temporary file (`Temp.dat`) during deletion.

## How to Run

1. Open the project in a C compiler that supports Windows headers like `windows.h` and `conio.h` (e.g. Turbo C++, Code::Blocks on Windows).
2. Compile the file `employee-record-system.c`
3. Run the compiled program.
4. Use the numbered menu to interact with the system.

## Requirements

- Windows-based system (uses `windows.h`, `conio.h`)
- C compiler (GCC, Turbo C++, Code::Blocks, etc.)

## Note

- This project is for educational purposes and demonstrates basic C concepts like structures, file handling, and simple user interaction.
- Data is stored in binary format, so you won’t be able to read `EMP.DAT` directly using a text editor.


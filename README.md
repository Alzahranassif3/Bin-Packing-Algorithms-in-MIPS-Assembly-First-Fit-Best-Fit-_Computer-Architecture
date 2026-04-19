# Bin Packing Algorithms in MIPS Assembly

## 📖 Overview

This project implements bin packing algorithms using MIPS Assembly language.
It reads floating-point values from a file (between 0 and 1) and distributes them into bins of size 1.0 using different allocation strategies.

## ⚙️ Technologies Used

* MIPS Assembly
* MARS / SPIM Simulator
* File I/O (syscalls)
* Floating-point operations

## 🧩 Implemented Algorithms

* First Fit Algorithm

  * Places each item in the first available bin that fits

* Best Fit Algorithm

  * Places each item in the bin with the least remaining space that can still fit it

## 🚀 Key Features

* File input handling and validation
* Parsing and converting strings to floating-point values
* Dynamic bin allocation and tracking
* Menu-driven interface for user interaction
* Output results displayed and saved to file

## 🧪 Validation

* Ensures all input values are within range (0–1)
* Handles invalid file paths and formats
* Prevents incorrect data processing

## 📊 Output

* Displays:

  * Bin index
  * Remaining size
  * Values inside each bin
* Calculates minimum number of bins used


## 📌 Conclusion

This project demonstrates how complex algorithms like bin packing can be implemented efficiently at a low level using assembly language, highlighting control over memory and performance.

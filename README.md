# 📅 Date Management System (C++)

A robust, object-oriented C++ library designed for precise date manipulation and management. This system provides a clean interface for handling calendar operations, specifically tailored for engineering applications and software development projects.

---

## 🌟 Key Features
* Encapsulated Logic: Fully utilizes Object-Oriented Programming principles to ensure data integrity and modularity.
* Validation Engine: Built-in methods to verify date validity, accounting for leap years and varying month lengths.
* Mathematical Operations: Supports arithmetic operations, allowing seamless addition and subtraction of days.
* Customizable Formatting: Flexible display options to accommodate various international date formats.

## 🛠 Tech Stack
* Language: C++ (MSVC - Microsoft Visual Studio specific, due to __declspec(property) extension)
* Environment: Developed and tested in Microsoft Visual Studio.

## 🚀 Getting Started
1. Clone the repository:
   git clone [YOUR_REPOSITORY_LINK]

2. Integrate: Include the required header files in your project:
   - `clsDate.h` (Main date library)
   - `clsString.h` (String utilities, required for splitting date strings)

3. Basic Usage:
   
```cpp
   #include "clsDate.h"
   #include <iostream>

   int main() {
       clsDate Date1(14, 7, 2026);
       Date1.Print();  // Outputs: 14/7/2026

       Date1.AddDays(10);  // Adds 10 days
       Date1.Print();      // Outputs: 24/7/2026

       std::cout << "Is 2024 a leap year? " << clsDate::isLeapYear(2024); // Outputs: 1 (true)
       return 0;
   }
```
📈 Engineering Roadmap

· Implement high-precision time-tracking (Hours, Minutes, Seconds).
· Develop complex duration-calculation algorithms between two points in time.
· Integration Module: Linking calendar events to automated hardware tasks (e.g., robotic arm task scheduling).

## 📚 Credits & Acknowledgments

This library is based on the educational content and code provided by Mohammed Abu-Hadhoud (ProgrammingAdvices.com).  
I have studied, understood, and customized the code for my personal learning and portfolio.

Maintainer: Shahad Al-Amin (Electrical Engineering Student, Qassim University)

📝 License

This project is licensed under the MIT License.
This project is licensed under the MIT License.

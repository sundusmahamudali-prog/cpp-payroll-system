# 💸 C++ Payroll & Employee Management System

This project is a comprehensive payroll engine developed as part of my studies at **Rathmines College**. It manages employee records and calculates detailed Irish tax deductions.

## 🚀 Key Technical Features
* [cite_start]**Inheritance**: The system uses a base class `new_employee` and a derived class `perm_employee` to manage different data levels.
* [cite_start]**Encapsulation**: Private data members (like `dm_gross` and `dm_PAYE`) ensure that sensitive financial data is protected and only modified through specific methods[cite: 8].
* **Irish Tax Logic**: The system accurately calculates:
    * [cite_start]**PAYE**: Based on single or coupled status (SRCOP)[cite: 8].
    * [cite_start]**USC**: Using multi-tiered percentage brackets[cite: 8].
    * [cite_start]**PRSI**: Calculated at a flat 4% rate[cite: 8].

## 🏗️ Code Structure
* [cite_start]**`payroll.cpp`**: Contains the `Payroll` class, which handles all mathematical calculations and payslip formatting[cite: 8].
* [cite_start]**`new_employee.cpp`**: Manages user input, stores multiple employee records in arrays, and generates a summary report.

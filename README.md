# Bank Account Simulation

## Overview
This project simulates basic **banking operations** using **Object-Oriented Programming (OOP)** in Java.  
It models real-world account behavior like deposits, withdrawals, interest addition, and overdraft handling — demonstrating **inheritance**, **method overriding**, and **encapsulation**.  

The system is **menu-driven** and fully **interactive**, allowing users to create either a **Savings Account** or a **Current Account** and perform transactions dynamically.

---

## Project Approach
This project follows a **modular, OOP-based architecture**.  
Each class represents a clear responsibility and contributes to a scalable, maintainable structure.

### Class Design
| Class | Description |
|--------|--------------|
| **`Account` (Abstract Class)** | Defines core attributes (account number, holder, balance) and shared behaviors such as deposit, withdraw, and transaction logging. |
| **`SavingsAccount`** | Inherits from `Account`. Adds interest calculation and demonstrates method overriding. |
| **`CurrentAccount`** | Inherits from `Account`. Implements overdraft functionality and overrides withdraw logic. |
| **`Main`** | Acts as the entry point. Handles user input, displays the menu, and performs operations interactively. |

---

## Key Concepts Implemented
- **Inheritance** → Shared structure and behavior via base class.  
- **Method Overriding** → Customized functionality for different account types.  
- **Encapsulation** → Controlled access to account data and balance.  
- **Polymorphism** → Dynamic behavior based on account type at runtime.  
- **Abstraction** → Abstract methods for flexible class extension.

---

## Implementation Highlights
- **Transaction History** – Every operation is logged with timestamps.  
- **Interest Calculation** – Savings accounts can add interest to balance.  
- **Overdraft Limit** – Current accounts simulate real-world overdraft rules.  
-  **User Interaction** – Fully menu-driven console interface.  
- **Java 8 Compatibility** – Uses classic syntax for universal support.

---




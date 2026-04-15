# Secure Banking (Embedded)
An Arduino-based embedded simulation of the secure_cpp_banking system. Features keypad input, LCD output, EEPROM storage, and a menu-driven ATM system.
## Description
A simple banking system built in C++ that supports account management and basic transactions using file handling.

## Features
- User login system
- Create account
- Deposit money
- Withdraw money
- Transfer money
- File-based data storage

## Build & Run

```bash
g++ main.cpp Account.cpp Bank.cpp User.cpp -o banking_app
./banking_app

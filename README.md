Bank Management System
Overview
The Bank Management System is a simple C program designed to simulate basic banking operations. It enables bank employees to perform essential tasks such as creating and managing customer accounts, handling transactions, and retrieving customer details. This application is intended for use in a standalone environment to streamline banking workflows.

Features
Account Management:

Add new customer accounts.
Update customer details (address and phone number).
Delete customer accounts.
Transaction Handling:

Deposit and withdraw money from accounts.
Ensure compliance with minimum balance requirements for savings accounts.
Customer Information Retrieval:

View the list of all customers.
Search for customer details by account number or name.
Interest Calculation:

Calculate and display interest for savings accounts.
How It Works
Data Storage: The application uses a file (record.dat) to store customer details persistently. All operations such as adding, updating, or deleting accounts modify this file.

Menu-Driven Interface: The program uses a simple, user-friendly menu system to navigate between functionalities.

Account Types:

Savings: Requires a minimum balance of ₹2000.
Current: No minimum balance requirement.
Security Features:

Prevents duplicate account numbers.
Validates operations to ensure minimum balance is maintained for savings accounts.
Usage
Running the Program
Compile the program using a C compiler (e.g., GCC).
Run the executable file to access the main menu.
Navigation
Follow the on-screen instructions to perform operations.
Options include account creation, editing, deleting, viewing customer lists, and handling transactions.
Prerequisites
C Compiler: Ensure a C compiler like GCC is installed.
Operating System: Windows (uses <windows.h> for console operations).
Limitations
Single-user system: Does not support concurrent access or multi-threading.
Simple file-based storage: Lacks the robustness of a database system.
Future Enhancements
Potential improvements include:

Implementing a GUI for a more interactive user experience.
Migrating to a database system for better data management and scalability.
Adding support for additional account types and features.
Feel free to copy or adapt this content as needed for your repository!

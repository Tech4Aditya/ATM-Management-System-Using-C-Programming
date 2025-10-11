# ATM-Management-System-Using-C-Programming

《《《Project Synopsis》》》

# ATM Management System Using C Programming

# —Group Members—

1)Aditya Pandey
2)Akriti Srivastava
3)Manya Rastogi
4)Manan Bhatia

# 「 ✦ Brief Description: ✦ 」

# ➤Objective:
The aim of this project is to develop a simple and efficient ATM (Automated Teller Machine)
Management System using C programming. This system simulates real-world banking
operations and allows users to perform basic financial transactions securely.
# ➤Description:
The ATM Management System is a console-based application written in C that enables users
to access their bank accounts and perform transactions such as balance enquiry, cash
withdrawal, cash deposit, and PIN change. The system authenticates users through a unique
account number and PIN, ensuring security and privacy.
The project is designed to familiarize students with file handling, functions, arrays, loops,
and conditional statements in C while simulating a practical banking environment. It
emphasizes security, error handling, and user-friendly interaction.
This project is highly useful for understanding how software can solve real-world problems
by mapping user interactions to data structures and control flows.

# ➤Features:
# ➤User Authentication
⤷Login via account number and PIN.
⤷Security measure: blocks multiple invalid attempts.
# ➤Cash Withdrawal
⤷Withdraw specified amounts.
⤷Ensures sufficient balance is available.
# ➤Cash Deposit
⤷Deposit money into the account.
⤷Updates the account balance in real-time.
# ➤Balance Enquiry
⤷Display the current balance.
# ➤PIN Change
⤷Allows the user to update their PIN.
# ➤Mini Statement (optional advanced feature)
⤷Shows recent transactions for transparency.
# ➤Persistent Data Storage

⤷Stores account information and transactions using file handling.

# ➤Software Requirement Specification (SRS):
# ➤Software:

# ⓘC Compiler (e.g., GCC)

# ⓘText Editor or IDE (Code::Blocks, Dev-C++, or Visual Studio Code)

# ➤Hardware:

# ⓘMinimum 1 GB RAM

# ⓘProcessor: Intel Core i3 or equivalent

# ⓘStorage: 100 MB free space

# ➤Operating System:

# ⓘWindows/Linux/MacOS terminal support

# ╰┈➤System Elements &amp; Diagram:
# Data Structures Used:
# ➤Structures: Used to define an account with fields like account number, PIN, balance,
and transaction history.
# ➤Arrays: Store recent transactions or multiple account details.

# ➤File Handling: Used to persistently store account information and update records.

Control Flow:
➤Decision-making (if-else) for PIN verification, balance checks, and withdrawal limits.

➤Loops (while/do-while) for repeating menu-driven options until the user exits.

➤Function calls for modular operations like deposit, withdraw, and balance enquiry.

╰┈➤Class Diagram / Structure Diagram (simplified):
+-----------------+
| Account |
+-----------------+
| accountNumber |
| pin |
| balance |
| transactions[] |
+-----------------+
| checkBalance() |
| deposit() |
| withdraw() |
| changePIN() |
| miniStatement() |
+-----------------+

This structure directly maps to real-life ATM functionalities where each account object
represents a bank customer. Functions act as operations performed at the ATM.

➤Mapping to Real-Life Applications:


# 「 ✦ Expected Outcome ✦ 」
Efficient simulation of ATM banking operations.

Enhanced understanding o C programming constructs.

Hands-on experience wit data storage, modular design, and secure user
authentication.

Clear connection betwee software logic and real-world banking applications.

**Overview:**

Ultra Wallet is a C++ console-based digital payment system that simulates a real-world e-wallet application. It allows users to perform financial transactions such as:

Adding money to their wallet

Sending money to other users

Purchasing mobile load (Easy Load)

Paying utility bills (Gas, Water, Electricity)

The system includes secure PIN entry, credit card encryption, and transaction logging for security and record-keeping.

**✨ Key Features**
1. User Authentication
Secure username login (sara_88 or pflab88fail)

Masked PIN entry for security

2. Financial Transactions
Add Money: Deposit funds via linked bank accounts (Allied Bank, UBL, HBL)

Send Money: Transfer money to another Ultra Wallet user

Easy Load: Purchase mobile credit for Zong, Jazz, or Ufone

Bill Payment: Pay gas, water, or electricity bills

3. Security & Encryption
Credit Card Encryption: Stores card numbers in an encrypted format

Transaction Logs: Records all transactions in .txt files

4. User-Friendly Interface
Interactive menu-driven system

Balance tracking before and after each transaction

**⚙️ Technical Implementation
🔹 Core Functions**
mask(): Securely hides PIN input with asterisks (****)

id_number(string n): Encrypts credit card numbers for secure storage

File Handling: Logs transactions in:

add_money.txt

send_money.txt

easy_load.txt

bill_payment.txt

final.txt (consolidated transaction log)

🔹 Data Validation
Credit Card Number: Must be 14 digits

Phone Number: Must be 10 digits (Pakistan format: +92XXXXXXXXXX)

Bill Number: Must be 10 digits

Balance Checks: Prevents over-withdrawal

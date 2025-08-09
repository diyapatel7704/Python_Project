💳 Online GPay Payment Simulation System (Python, OOPs)

📌 Overview

The Online GPay Payment Simulation System is a console-based Python project that replicates core functionalities of Google Pay using Object-Oriented Programming (OOP) principles.
It supports user and merchant registration, secure UPI PIN-based transactions, wallet balance management, and transaction history tracking.

🚀 Features

User & Merchant Registration with unique phone numbers.

Secure Transactions with UPI PIN verification.

Wallet Management:

Add money

Deduct money

Check balance

Transaction History tracking for each user.

Encapsulation for UPI PIN security.

OOP Design:

Encapsulation (private data members)

Inheritance (Merchant inherits User)

Composition (User HAS-A Wallet)

Polymorphism for flexible transaction handling.

🛠 Technologies Used
Python 3.x

DateTime module (for transaction timestamps)

Object-Oriented Programming Concepts

📂 Project Structure

perl
Copy
Edit
gpay-system/
│
├── gpay_system.py        # Main script
├── README.md             # Project documentation

⚙️ How It Works

Register Users and Merchants.

Add Money to the wallet.

Send Money between users or to merchants.

Verify UPI PIN before processing the payment.

View Transaction History to see past transactions.

🖥 Sample Output

pgsql
Copy
Edit
User Diya Registered Successfully!
Merchant Rahul Registered Successfully!
₹5000 added to wallet. Current Balance: ₹5000
Wallet Balance: ₹5000
Wallet Balance: ₹0
Transaction of ₹1500 Successful from Diya to Rahul
---- Transaction History ----
2025-08-04 17:30:45.123456 | Diya sent ₹1500 to Rahul

📦 Installation & Usage

Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/gpay-system.git
cd gpay-system
Run the Python script

bash
Copy
Edit
python gpay_system.py

📈 Future Enhancements

Bank account linking for wallet recharge.

QR code-based payment system.

Interest on wallet balance.

Multi-factor authentication.

👩‍💻 Author
Diya Patel – GitHub Profile | LinkedIn

If you want, I can also make a professional GitHub repo for this with separate files (models.py, main.py) so it looks like a real-world structured project.

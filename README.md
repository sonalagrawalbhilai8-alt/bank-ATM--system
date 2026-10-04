# 🏧 ATM Simulator System

A **Java-based ATM Simulator System** that provides a graphical interface for performing common ATM operations such as account registration, login, cash withdrawal, deposits, balance enquiry, fast cash, mini statements, and PIN management.

## 📌 About the Project

The ATM Simulator System is a desktop-based banking application developed using **Java Swing** and connected to a **MySQL database**.

It simulates the basic functionality of an ATM and allows users to create an account, authenticate themselves, and perform different banking transactions.

## ✨ Features

### 🔐 User Authentication
- User login using card number and PIN
- Multi-step account registration
- PIN-based authentication

### 📝 Account Registration

New users can register by providing their personal and account-related information.

The registration process is divided into multiple steps:

- Personal information
- Additional details
- Account and card details

### 💰 Banking Operations

The application provides several ATM operations:

- 💵 Cash withdrawal
- 💳 Cash deposit
- ⚡ Fast cash
- 💰 Balance enquiry
- 📄 Mini statement
- 🔑 PIN change
- 🔄 Transaction management

### 📊 Transaction History

Users can view their recent transactions through the mini statement feature.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Java** | Core programming language |
| **Java Swing** | Graphical User Interface |
| **AWT** | GUI components and event handling |
| **JDBC** | Database connectivity |
| **MySQL** | Database management |
| **NetBeans** | Development environment |

## 📁 Project Structure

```text
ATM-Simulator-System/
│
├── ATM-Simulator-System/
│   │
│   ├── src/
│   │   └── ASimulatorSystem/
│   │       ├── BalanceEquiry.java
│   │       ├── Conn.java
│   │       ├── Deposit.java
│   │       ├── FastCash.java
│   │       ├── Login.java
│   │       ├── MiniStatement.java
│   │       ├── Pin.java
│   │       ├── Practice.java
│   │       ├── Signup.java
│   │       ├── Signup2.java
│   │       ├── Signup3.java
│   │       ├── Transactions.java
│   │       ├── Withdrawl.java
│   │       └── icons/
│   │
│   ├── nbproject/
│   ├── build.xml
│   └── manifest.mf
│
├── .gitignore
└── README.md
```

## ⚙️ Requirements

Before running the application, install:

- **Java JDK**
- **NetBeans IDE** (recommended)
- **MySQL Server**
- **MySQL Connector/J**
- Required Java libraries/dependencies

Check your Java installation:

```bash
java -version
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/atm-simulator-system.git
```

Replace `your-username` with your GitHub username.

### 2. Open the Project

Open **NetBeans IDE** and select:

```text
File → Open Project
```

Select the `ATM-Simulator-System` project.

### 3. Configure MySQL

The project uses MySQL for storing account and transaction information.

Open:

```text
src/ASimulatorSystem/Conn.java
```

Configure the database connection according to your local MySQL setup.

You will need to create the required database and tables before running the application.

### 4. Add Required Dependencies

Make sure the **MySQL JDBC driver** is added to the project libraries.

### 5. Run the Application

Run:

```text
Login.java
```

The application will open the ATM login interface.

## 🔄 Application Workflow

```text
                    ATM SYSTEM
                        │
                        ▼
                     Login
                        │
              ┌─────────┴─────────┐
              │                   │
          New User            Existing User
              │                   │
          Sign Up              Enter PIN
              │                   │
              └─────────┬─────────┘
                        ▼
                  Transactions
                        │
        ┌───────────────┼────────────────┐
        │               │                │
        ▼               ▼                ▼
     Deposit         Withdrawl       Fast Cash
        │               │                │
        └───────────────┼────────────────┘
                        │
              ┌─────────┴─────────┐
              ▼                   ▼
        Balance Enquiry      Mini Statement
                                  │
                                  ▼
                              PIN Change
```

## 💳 ATM Operations

### 💵 Deposit

Users can deposit money into their account.

### 💸 Withdrawal

Users can withdraw a specified amount from their available balance.

### ⚡ Fast Cash

Allows users to quickly withdraw predefined amounts.

### 💰 Balance Enquiry

Displays the current account balance.

### 📄 Mini Statement

Displays recent account transactions.

### 🔑 PIN Change

Allows users to change their ATM PIN.

## 🗄️ Database

The application uses **MySQL** as its database.

Java connects to MySQL using **JDBC**.

The `Conn.java` class is responsible for establishing the database connection.

The database stores information related to:

- Customer accounts
- Card numbers
- PINs
- Account details
- Transactions
- Deposits
- Withdrawals

## 📚 Learning Objectives

This project demonstrates practical implementation of:

- Java programming
- Object-Oriented Programming
- Java Swing
- GUI development
- Event handling
- JDBC
- MySQL
- CRUD operations
- Database connectivity
- Form validation
- Transaction management

## 🔮 Future Improvements

The project can be enhanced with:

- 🔐 Stronger authentication
- 🔒 Password/PIN encryption
- 📱 Mobile banking interface
- 🌐 Web-based version
- 📊 Admin dashboard
- 📧 Transaction notifications
- 🧾 PDF statement generation
- 💳 Real payment gateway integration
- 📈 Transaction analytics
- ☁️ Cloud database support
- 🛡️ Improved security and fraud detection

## ⚠️ Security Notice

This project is intended for **educational and demonstration purposes**.

Do not use real banking credentials, real card numbers, PINs, or financial information while testing the application.

Never upload database passwords, API keys, or other sensitive credentials to a public GitHub repository.

## 🤝 Contribution

Contributions and improvements are welcome.

To contribute:

```bash
git clone https://github.com/your-username/atm-simulator-system.git
```

Create a new branch:

```bash
git checkout -b feature/new-feature
```

Make your changes, commit them, and create a pull request.



## 👩‍💻 Author

**Sonal Agrawal**

B.Tech Computer Science Engineering (AI)

---

⭐ If you find this project useful, consider giving the repository a star!

# 🏦 Small Bank System – C++ Project

This project represents a **Small Bank System** built using **C++**, developed as part of my *Programming Advices* learning journey at **Level 07 (Algorithm03 & Problem Solving)**.  
It focuses on applying algorithmic thinking and structured programming to simulate real-world banking operations in a modular, console-based application.

---

## ✨ Project Overview

The system allows managing bank clients and performing core financial operations with persistent storage via text files.  
It’s organized into clearly separated menus for **client management** and **transactions**, emphasizing clean design, maintainability, and logical problem solving.

---

## 🧩 Features

### 🔹 Client Management
- **Show All Clients** – Display a list of all existing clients with formatted output.  
- **Add New Client** – Register new clients after verifying unique account numbers.  
- **Delete Client** – Remove client records safely with confirmation.  
- **Update Client Information** – Modify an existing client’s data.  
- **Find Client** – Search for a specific client using the account number.

### 💰 Transactions
- **Deposit** – Add funds to an account.  
- **Withdraw** – Deduct funds while validating balance availability.  
- **Total Balances** – Display all client balances and compute the total sum.

### 💾 File Handling & Data Persistence
- Stores all client data in a text file (`Clients.txt`).
- Converts records seamlessly between structured objects and text lines using:
  - `ConvertRecordToLine()`
  - `ConvertLineToRecord()`
  - `SplitString()`
- Supports full data reload after updates or deletions.

---

## 🧠 Learning Objectives

- Strengthen **algorithmic problem-solving** through practical application.  
- Implement **structured and modular design** using functions and enums.  
- Gain experience with **file I/O operations** in C++.  
- Apply **clean code practices** and logical program flow design.  
- Practice building **menu-driven systems** for real-world simulations.

---

## ⚙️ Technical Details

| Category | Details |
|-----------|----------|
| **Language** | C++ |
| **Concepts Used** | Functions, Structs, Enums, Loops, File Streams, Vectors |
| **Data Storage** | Text File (`Clients.txt`) |
| **Environment** | Visual Studio / Code::Blocks / Any C++ Compiler |
| **Project Level** | Level 07 – Algorithm03 & Problem Solving |

---

## 🧭 Program Flow Overview

**Main Menu →**  
1️⃣ Show Client List  
2️⃣ Add New Client  
3️⃣ Delete Client  
4️⃣ Update Client Info  
5️⃣ Find Client  
6️⃣ Transactions Menu → Deposit / Withdraw / Total Balances  
7️⃣ Exit

---

> 🧠 *Developed as part of my continuous learning journey with Programming Advices, focusing on applying algorithms to practical programming problems and improving real-world coding efficiency.*

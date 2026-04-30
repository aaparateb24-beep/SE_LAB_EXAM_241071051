
# 📚 Smart Library Management System (SLMS)
### **Software Engineering Lab | Q2: Implementation & Testing**
**Institute:** Veermata Jijabai Technological Institute (VJTI)  

---

##  Overview
The **Smart Library Management System** is a robust Python-based implementation of the "Book Issue" use case. This project demonstrates the practical application of **Object-Oriented Programming (OOP)**, **Custom Exception Handling**, and **Automated Testing Methodologies**. 

The system doesn't just issue books; it enforces strict institutional policies including membership activity, fine thresholds, and borrowing limits to ensure data integrity.

---

## Key Features
* **Encapsulated Architecture:** Utilizes `Member`, `Book`, and `LibrarySystem` classes for clean state management.
* **Validation Engine:** A multi-tier check system for:
    * Member Activity Status.
    * Fine Balance Enforcement (Blocks issues if fines > 0).
    * Borrowing Limit Verification (Max 5 books).
* **State Persistence:** Real-time tracking of book availability and member borrowing history.
* **Custom Exceptions:** Implements `MemberNotFoundError`, `BookNotFoundError`, and `ValidationError` for professional error reporting.

---

##  Testing Strategy
To ensure the highest reliability, the system includes an **Automated Test Suite** consisting of **30 distinct test cases**.

### **1. Black Box Testing (15 Cases)**
Focused on the **functional requirements** using:
* **Equivalence Class Partitioning:** Testing valid and invalid input ranges.
* **Boundary Value Analysis (BVA):** Testing minimum and maximum ID lengths and limits.

### **2. White Box Testing (15 Cases)**
Focused on **structural coverage** to ensure code reliability:
* **Statement Coverage:** 100% of the `issue_book` logic is executed.
* **Branch/Decision Coverage:** Validates both "True" and "False" outcomes for every `if` statement (e.g., active vs. inactive members).



---

## Execution Dashboard
The system provides a clear, tabular output in the terminal for the instructor to review.

| Metric | Result |
| :--- | :--- |
| **Total Test Cases Run** | 30 |
| **Successful Issues** | 26 (Happy Path) |
| **Caught Exceptions** | 4 (Negative Testing) |
| **Overall Success Rate** | **86.7%** |
| **Critical Path Coverage** | **100%** |

---

## 🖥️ Command Line Interface (CLI)
The program features a user-friendly CLI with the following options:
1.  **Run Automated Tests:** Instantly executes all 30 cases and generates a **Coverage Report**.
2.  **Add Member/Book:** Manually populate the library database.
3.  **Issue Book:** Test individual transactions in real-time.

---

## 📂 Project Structure
```text
├── issue_book.py           # Core implementation & test suite
├── README.md               # Documentation & project overview
└── Test_Results.txt        # Exported terminal output for viva
```

---

## 🏁 How to Run
1.  Open the terminal on the iMac.
2.  Navigate to the directory containing the file.
3.  Execute: `python3 issue_book.py`.
4.  Select **Option 1** for the full automated evidence report.

---
*Developed for the Software Engineering Lab - VJTI 2026*

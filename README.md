# SE_LAB_EXAM_241071051
# Smart Library System - Book Issue Implementation
**Course:** Software Engineering Lab (Q2 Implementation)
**Institute:** VJTI

## Overview
This project implements the "Book Issue" use case using Object-Oriented Programming (OOP) in Python. The system validates member eligibility, book availability, and business constraints before processing an issue.

## Features Implemented
- **Encapsulation:** Data and logic are bundled within Member and Book classes.
- **Custom Exception Handling:** Specific errors (MemberNotFound, ValidationError) are used for robust processing.
- **State Management:** Tracking of book availability and member's issued list.

## Testing Strategy
A total of **30 test cases** were executed:
1. **Black Box Testing (15 cases):** Used Equivalence Class Partitioning and Boundary Value Analysis to verify requirements.
2. **White Box Testing (15 cases):** Targeted Statement Coverage and Branch Coverage to ensure all logical paths are executed.

## How to Run
1. Open terminal on the iMac.
2. Navigate to the folder.
3. Run the command: `python3 issue_book.py`

## Test Results Summary
- **Total Test Cases:** 30
- **Successes:** 26 (86.6%)
- **Intentional Failures (Negative Testing):** 4 (13.4%)

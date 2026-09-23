
# Equivalence Partitioning – Test Cases
### DATE:22-09-2026
## 📌 About

This repository contains **Equivalence Partitioning (EP)** exercises and test cases created as part of **Software Testing / Manual Testing practice**.

Equivalence Partitioning is a black-box testing technique used to divide the input data of an application into different **equivalence classes**, where each class is expected to behave similarly.

Instead of testing every possible input, we select representative test values from each valid and invalid partition.

---

## 📂 Contents

The repository contains an Excel file with questions, equivalence partitions, and suitable test values for the following exercises:

1. **Marks Input Validation**

   * Valid range: 0–100
   * Identification of valid and invalid equivalence classes

2. **ATM Withdrawal Validation**

   * Valid range: ₹500–₹20,000
   * Identification of valid and invalid withdrawal amount partitions

3. **Username Validation**

   * Valid length: 5–15 characters
   * Identification of valid and invalid username length partitions

4. **Mobile Number Validation**

   * Valid length: Exactly 10 digits
   * Identification of valid and invalid length partitions

5. **Shopping Cart Quantity**

   * Valid quantity: 1–10 items
   * Identification of valid and invalid quantity partitions

6. **Bank Account Balance**

   * Minimum balance: ₹1,000
   * Maximum balance: ₹10,00,000
   * Identification of valid and invalid balance partitions

7. **Employee Salary**

   * Valid range: ₹15,000–₹2,00,000
   * Creation of EP test cases

8. **Movie Ticket Booking**

   * Valid booking quantity: 1–6 tickets
   * Identification of valid and invalid ticket quantity partitions

---

## 🧪 Testing Technique Used

### Equivalence Partitioning

The input domain is divided into:

* **Valid Equivalence Class** – Inputs that should be accepted by the application.
* **Invalid Equivalence Class** – Inputs that should be rejected by the application.

A representative test value is selected from each partition.

### Example

For a marks field where the valid range is **0–100**:

| Partition | Input Range      | Example |
| --------- | ---------------- | ------: |
| Invalid   | Less than 0      |      -1 |
| Valid     | 0–100            |      50 |
| Invalid   | Greater than 100 |     101 |

Testing these representative values helps reduce the number of test cases while still covering different input categories.

---

## 📊 File Included

**`task22september2026.xlsx`**

The Excel file contains:

* Exercise / Question
* Requirement
* Equivalence Partition
* Valid / Invalid Classification
* Input Range
* Suitable Test Value

---

## 🎯 Objective

The objective of these exercises is to practice:

* Understanding software requirements
* Identifying equivalence classes
* Separating valid and invalid inputs
* Selecting representative test data
* Creating structured manual testing test cases
* Applying black-box testing techniques

---

## 🛠️ Tools Used

* Microsoft Excel
* Manual Testing
* Equivalence Partitioning
* Git
* GitHub

---

## 👩‍💻 Author

**Oviya P**
B.E. Computer Science and Engineering (IoT)

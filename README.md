# C++ Programs: Decision Control and Loop Statements

This repository contains basic **C++ programs** focusing on **decision control and loop statements**, which are essential for understanding program flow and iteration.

---

## 1. Print Even Numbers from 1 to 20 Using While Loop

**Logic:**  
A variable `i` is initialized to 1. The `while` loop checks if `i` is less than or equal to 20.  
Inside the loop, it checks if `i` is divisible by 2 (i.e., `i % 2 == 0`). If so, it prints the number.  
Then, `i` is incremented by 1.

**Theory:**  
The `while` loop is an **entry-controlled loop**, meaning it checks the condition before executing the loop body.  
This method is suitable when we want to process a range of values and apply conditional checks within the loop.

**Concepts Covered:**

- Looping constructs  
- Entry-controlled loop  
- Conditional execution inside loop

## 3. Print "SIT" 5 Times Using For Loop

**Logic:**  
A `for` loop runs from 0 to 5 and prints `"SIT"` in each iteration (6 times total).

**Theory:**  
The `for` loop is ideal for **fixed-count iterations**, consisting of initialization, condition checking, and updating.

**Concepts Covered:**

- For loop structure  
- Fixed iteration  
- Output repetition  

---

## 4. Print Even Numbers from 0 to 10 Using For Loop

**Logic:**  
A loop runs from 0 to 10 and prints numbers only if they satisfy the condition `i % 2 == 0`.

**Theory:**  
The modulo operation (`%`) is used to test divisibility.  
Combining conditionals with loops allows **filtering values**.

**Concepts Covered:**

- Conditional checks in a loop  
- Modulus operator  
- Filtering output  

---



---

## 6. Limited Attempts for System Lock

**Logic:**  
The user gets 3 attempts to input the correct password.  
Each failed attempt reduces the available tries.  
On correct input, access is granted; otherwise, the system locks.

**Theory:**  
Combining loops and conditionals can simulate **basic authentication systems**.

**Concepts Covered:**

- While loop  
- Authentication logic  
- Loop termination  

---



## Pattern Programs

These C++ programs demonstrate various star and number patterns using nested loops. They are excellent practice for mastering loop control and formatting output in structured ways.

---

### Inverted Right-Angle Triangle

**Filename:** `inverted right angle triangle.cpp`

**Description:**  
Prints a star pattern where the number of stars decreases with each row, forming an inverted right-angled triangle.

**Example Output:**

## Conclusion

These programs help us **build a strong foundation in loops, conditionals, and flow control in C++**.  
They offer hands-on examples for understanding essential logic structures used in real-world applications.

---

### Number triangle Pattern

**Description:**  
Prints Floyd's Triangle — a right-angled triangle of sequential natural numbers where each row contains an increasing number of elements.

**Logic Overview:**  
- Uses nested loops.
- A counter variable is initialized to 1.
- Outer loop runs for each row.
- Inner loop prints increasing numbers using the counter and increments it after each print.

**Example Structure (n = 5 rows):**
---

## Increment Star Pattern (Left-Aligned Triangle)

**Logic:**  
The outer loop controls rows, and the inner loop prints `*` equal to the row number.  
Stars increase with each row.

**Theory:**  
**Nested loops** can generate structured text-based patterns.

**Concepts Covered:**

- Nested loops  
- Pattern building  
- Output formatting  

---

## Mirror Image Star Pattern (Right-Aligned Triangle)

**Logic:**  
The outer loop handles rows.  
The first inner loop prints spaces to shift stars, and the second inner loop prints `*`.

**Theory:**  
Right-aligned patterns require controlling both **spacing and symbols**.

**Concepts Covered:**

- Alignment logic  
- Nested loops  
- Visual formatting  

---


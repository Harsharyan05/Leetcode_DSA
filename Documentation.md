# 📅 Day 01 – 27 June 2026

## Problems Solved

### 1. Reverse Integer (#7)

**Difficulty:** Medium

**Approach**

* Extract the last digit using `% 10`.
* Remove the last digit using `/ 10`.
* Build the reversed integer using `rev = rev * 10 + digit`.
* Handle integer overflow using `INT_MAX` and `INT_MIN`.

**Concepts Learned**

* Modulo & Division
* Integer Overflow
* Number Manipulation

---

### 2. Number Complement (#476)

**Difficulty:** Easy

**Approach**

* Create a bit mask containing all `1`s up to the most significant bit.
* Use XOR (`^`) with the mask to flip all bits.
* Handle the special case when `n = 0`.

**Concepts Learned**

* Binary Representation
* XOR
* Bit Masking
* Left & Right Shift

---

### 3. Number of 1 Bits (#191)

**Difficulty:** Easy

**Approach**

* Use Brian Kernighan's Algorithm.
* Repeatedly perform:

  ```cpp
  n = n & (n - 1);
  ```
* Count how many times the operation is performed until `n` becomes `0`.

**Concepts Learned**

* Set Bits
* Bit Manipulation
* Binary Operations

---

### 4. Power of Two (#231)

**Difficulty:** Easy

**Approach**

* Reject all numbers less than or equal to zero.
* Use:

  ```cpp
  n & (n - 1)
  ```
* If the result is `0`, the number is a power of two.

**Concepts Learned**

* Power of Two Property
* Bitwise AND
* Set Bits

---

# Key Learnings

* Learned binary representation of integers.
* Understood bitwise operators (`&`, `|`, `^`, `<<`, `>>`).
* Learned how to create bit masks.
* Learned Brian Kernighan's Algorithm.
* Understood integer overflow handling.
* Practiced solving problems using optimal bit manipulation techniques.

---

## Statistics

* Problems Solved: **4**
* Easy: **3**
* Medium: **1**
* Hard: **0**

### Topics Covered

* Bit Manipulation
* Mathematics
* Binary Numbers
* Number Theory
* Integer Operations
-----------------------------------------------------------------------------------------------

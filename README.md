# Arithmetic_Operations-TA-Notes

## About This Repository

I am a Teaching Assistant for the Intro to C Programming course (January 2026 to April 2026), and this repository contains lab instruction materials and example programs created to help students during lab sessions.

## Overview
This repository contains instructional materials and example programs used during Intro to C Programming lab sessions. Lab 2 focuses on arithmetic operations, integer vs float division, type casting, and operator precedence—fundamental concepts that students often find tricky when starting with C programming.

These materials were designed to help beginner programmers understand not just the "how" but also the "why" behind C's arithmetic behavior, with plenty of examples showing common mistakes and how to avoid them.

## Skills Demonstrated
- Teaching Assistant experience in Introductory C Programming
- Mentoring and supporting beginner-level computer science students
- C programming fundamentals (arithmetic operators, type casting, operator precedence)
- Explaining the difference between integer and floating-point division
- Debugging common arithmetic pitfalls and type conversion issues
- Code quality best practices (readability, explicit casting, proper use of parentheses)
- Technical communication and instructional design for programming labs
- Academic leadership, classroom facilitation, and student support

## What I Taught in Lab Sessions
During Lab 2, I guided students through the following core concepts:
### 1. Arithmetic Operators in C
- Basic operators: +, -, *, /, %
- How each operator works with different data types
- Understanding the modulus operator and when to use it

## 2. Integer Division vs Float Division
## 2. Integer Division vs Float Division in C

In C, the **type of the operands** determines how division is performed.

### How C Handles Division
- If **both operands are integers**, C performs **integer division**.
- If **at least one operand is a float**, C performs **floating-point division**.

### Why `7 / 3` Gives `2` Instead of `2.333`
Both `7` and `3` are integers, so C uses **integer division**, which **truncates** the decimal part.

-- int / int → integer division
-- float / int → float division
-- int / float → float division
-- float / float → float division



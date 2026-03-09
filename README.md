# LeetCode Problem Solutions Repository

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![DSA](https://img.shields.io/badge/Data%20Structures%20&%20Algorithms-00599C?style=for-the-badge)
![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)

This repository contains my solutions to various **LeetCode coding problems**, focusing on **Data Structures, Algorithms, and coding interview preparation**.

The repository serves as a structured collection of solutions that document my **problem-solving journey, algorithm practice, and continuous improvement in competitive programming.**

---

## Table of Contents

1. [Introduction](#introduction)
2. [Repository Purpose](#repository-purpose)
3. [Topics Covered](#topics-covered)
4. [Problem Solving Approach](#problem-solving-approach)
5. [Technology Stack](#technology-stack)
6. [Getting Started](#getting-started)
7. [Sample Code](#sample-code)
8. [Contributing](#contributing)
9. [License](#license)

---

# Introduction

**LeetCode** is one of the most widely used platforms for practicing **Data Structures and Algorithms (DSA)** and preparing for technical interviews at top technology companies.

This repository includes solutions to various LeetCode problems solved during **DSA practice, coding challenges, and interview preparation**.

The solutions focus on:

- Writing **clean and efficient code**
- Understanding **core algorithmic concepts**
- Practicing **time and space complexity optimization**
- Improving **logical reasoning and problem-solving skills**

Problems range from **easy to hard difficulty levels**, covering a wide range of algorithmic concepts frequently asked in technical interviews.

---

# Repository Purpose

This repository serves as:

- A **collection of solved LeetCode problems**
- A **reference guide for Data Structures and Algorithms**
- A **practice log for coding interview preparation**
- A **demonstration of programming and analytical skills**

It helps track my progress in **algorithmic thinking and competitive programming.**

---

# Topics Covered

The solutions in this repository cover multiple important DSA topics such as:

- Arrays
- Strings
- Recursion
- Binary Search
- Sorting Algorithms
- Linked Lists
- Stacks
- Queues
- Hash Tables
- Trees
- Binary Search Trees
- Graph Algorithms
- Dynamic Programming
- Greedy Algorithms
- Backtracking
- Bit Manipulation

Additional problems and topics will continue to be added as I solve more challenges.

---

# Problem Solving Approach

The general approach used while solving problems includes:

### 1. Problem Understanding
Carefully analyzing the problem statement, input constraints, and expected outputs.

### 2. Algorithm Design
Designing an optimal solution by considering **time complexity and space complexity**.

### 3. Implementation
Writing clean, readable, and optimized code.

### 4. Testing
Testing solutions with **sample inputs and edge cases**.

---

# Technology Stack

### Programming Languages
- Java
- Python

### Core Concepts
- Data Structures
- Algorithms
- Problem Solving
- Competitive Programming

### Tools
- VS Code
- Git
- GitHub

---

# Getting Started

To explore the solutions locally:

### Clone the Repository


git clone https://github.com/your-username/LeetCode-Solutions.git


Navigate into the project directory:


cd LeetCode-Solutions


You can open and run individual solution files using your preferred IDE.

---

# Sample Code

Example Java solution for reversing a string using recursion:


class Solution {

public static String reverse(String str) {
    if(str.length() <= 1)
        return str;

    return reverse(str.substring(1)) + str.charAt(0);
}

public static void main(String[] args) {
    String s = "LeetCode";
    System.out.println(reverse(s));
}

}


---

# Contributing

Contributions are welcome.

Steps to contribute:

1. Fork the repository  
2. Create a new branch


git checkout -b feature/NewSolution


3. Commit your changes


git commit -m "Added new LeetCode problem solution"


4. Push to the branch


git push origin feature/NewSolution


5. Open a Pull Request

---

# License

This repository is licensed under the **MIT License**.

---

⭐ If you find this repository helpful, feel free to **star the repository and explore the solutions.**

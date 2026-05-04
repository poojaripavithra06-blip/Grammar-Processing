# Compiler Design Project – DSL Compiler & Grammar Analysis

## 📌 Project Description
This project consists of two main components:

1. **Grammar Processing (Left Recursion Detection)**
2. **End-to-End DSL Compiler**

The goal is to analyze grammar rules for parser readiness and design a simple compiler pipeline from DSL source code to intermediate representation.

---

## 🔹 Part 1: Grammar Processing

### 🎯 Objective
To detect **Left Recursion** and compute **Recursion Depth** from grammar production rules stored as raw strings.

### ⚙️ Features
- Extracts LHS and RHS from grammar rules
- Computes **Recursion_Depth**
- Generates flag **Has_Left_Recursion**
- Helps identify grammars unsuitable for top-down parsing

### 🧠 Example

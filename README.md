# 🔢 Kaprekar Quest Project

**Author**: Kaitlyn Kirt  
**Course**: CMOR 220  
**Term**: Spring 2024  
**Project**: Kaprekar Quest  
**Last Modified**: April 1, 2024  

---

## 📋 Overview

This project explores **Kaprekar’s process** for numbers of arbitrary digit length. The script applies the Kaprekar transformation to all valid n-digit integers, iteratively computing sequences and visualizing convergence behavior using matplotlib.

---

## 📂 Files

- `Project8.ipynb`: Main Jupyter notebook with full implementation and visualizations.
- `README.md`: Project documentation and usage instructions.

---

## 🧮 What is the Kaprekar Process?

Kaprekar’s process involves:
1. Taking an n-digit number.
2. Arranging its digits in ascending and descending order.
3. Subtracting the smaller number from the larger.
4. Repeating this process with the result.

Eventually, the process converges to a fixed point (Kaprekar constant) or enters a loop (Kaprekar hole).

---

## 🛠️ Requirements

```bash
pip install numpy matplotlib

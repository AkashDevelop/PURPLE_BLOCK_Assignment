# Best Trade Finder 📈

[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE) [![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/yourusername/yourrepo)

---

## Overview
This assignment is a simple coding challenge where the goal is to find the best **buy** and **sell** prices from a list of prices to maximize profit.  
For example, given the list `[5, 2, 1, 6, 9, 7]`, the best trade is to **buy at 1** and **sell at 9**.

---

## How It Works 🤔
- **Input:** A list of prices (e.g., `[5, 2, 1, 6, 9, 7]`).
- **Process:**  
  - **Step 1:** Traverse the list while keeping track of the lowest price seen so far.
  - **Step 2:** Calculate the potential profit at each price by subtracting the lowest price from the current price.
  - **Step 3:** Update the best trade if the calculated profit is greater than the maximum profit so far.
- **Output:** Returns the best buy and sell prices to maximize profit.

---

## How to Run 🚀
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/PURPLE_BLOCK_Assignment
   cd yourrepo

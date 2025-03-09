
[Youtube assessment practice](https://www.youtube.com/watch?v=a6bOMcrVNXQ&lc=UgyuqAPIpshl2b_qO5F4AaABAg)

[epic reddit](https://www.reddit.com/r/epicsystems/comments/1j4hqcs/paired_programming_section_in_final_interview/)

[17. Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
[306. Additive Number](https://leetcode.com/problems/additive-number/)
[728. Self Dividing Numbers](https://leetcode.com/problems/self-dividing-numbers/)

More good questions
[Company-Wise](https://company-wise-leetcode-farneet.netlify.app/)

[Paid playlist](https://leetcode.com/company/epic-systems/?favoriteSlug=epic-systems-thirty-days)

### CompanyWise Questions
| ID   | Title                 | Acceptance | Difficulty | Frequency | Leetcode Question Link                                                                                                             | Attempted? | Date Solved |
| ---- | --------------------- | ---------- | ---------- | --------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------- | ----------- |
| 306  | Additive Number       | 29.4%      | Medium     | 0.68%     | [![LeetCode](https://company-wise-leetcode-farneet.netlify.app/leetcode.svg)](https://leetcode.com/problems/additive-number)       |            |             |
| 54   | Spiral Matrix         | 34.1%      | Medium     | 0.43%     | [![LeetCode](https://company-wise-leetcode-farneet.netlify.app/leetcode.svg)](https://leetcode.com/problems/spiral-matrix)         |            |             |
| 38   | Count and Say         | 44.6%      | Easy       | 0.18%     | [![LeetCode](https://company-wise-leetcode-farneet.netlify.app/leetcode.svg)](https://leetcode.com/problems/count-and-say)         |            |             |
| 20   | Valid Parentheses     | 39.0%      | Easy       | 0.02%     | [![LeetCode](https://company-wise-leetcode-farneet.netlify.app/leetcode.svg)](https://leetcode.com/problems/valid-parentheses)     |            |             |
| 728  | Self Dividing Numbers | 74.3%      | Easy       | 0.00%     | [![LeetCode](https://company-wise-leetcode-farneet.netlify.app/leetcode.svg)](https://leetcode.com/problems/self-dividing-numbers) |            |             |
| 1215 | Stepping Numbers      | 41.6%      | Medium     | 0.00%     | [![LeetCode](https://company-wise-leetcode-farneet.netlify.app/leetcode.svg)](https://leetcode.com/problems/stepping-numbers)      |            |             |

### **3. Matrix Problems to Practice (LeetCode)**

🔹 **Easy:**

- 🔗 74. Search a 2D Matrix
- 🔗 733. Flood Fill

🔹 **Medium:**

- 🔗 48. Rotate Image
- 🔗 200. Number of Islands
- 🔗 54. Spiral Matrix

🔹 **Hard:**

- 🔗 329. Longest Increasing Path in a Matrix
- 🔗 85. Maximal Rectangle


### **3. Permutation Problems to Practice (LeetCode)**

🔹 **Easy:**

- 🔗 46. Permutations
- 🔗 31. Next Permutation

🔹 **Medium:**

- 🔗 47. Permutations II (Unique Permutations)
- 🔗 77. Combinations
- 🔗 78. Subsets

🔹 **Hard:**

- 🔗 996. Number of Squareful Arrays
- 🔗 60. Permutation Sequence




# Concepts
- **Understand Theoretical Concepts** → Review traversal, sorting, backtracking, and DP approaches.
- **Solve Easy Problems First** → Build confidence in basic traversal and recursion.
- **Use Dry Run & Debugging** → Print intermediate steps for recursion-based permutation problems.
- **Time Yourself in Practice** → Simulate test conditions (30-45 minutes per problem).
- **Master Recursion for Permutations** → Backtracking is essential for many problems.



## **1. String Permutations with Fixed Uppercase Positions**

**Difficulty: Medium**

### **Problem Statement:**

Given a string `s` containing both **uppercase and lowercase letters** (but no numbers or special characters), generate all possible permutations of `s` while keeping the **uppercase letters in their original positions**.

### **Constraints:**

- `1 ≤ len(s) ≤ 10`
- `s` contains **only English letters (a-z, A-Z)**.
- **Uppercase letters must remain in their original positions** while lowercase letters can be rearranged freely.

### **Example:**

#### **Input:**

python

CopyEdit

`s = "AbC"`

#### **Output:**

python

CopyEdit

`["AbC", "ACb", "bAC", "CbA", "bCA", "CbA"]`

---

## **2. Maximizing Captures on an n x n Chess-like Board**

**Difficulty: Hard**

### **Problem Statement:**

You are given an `n x n` board where:

- `'1'` represents your pieces.
- `'2'` represents opponent pieces.
- `'0'` represents an empty square.

One of your pieces has **fallen off**, and you can **place it anywhere** to **maximize** the number of opponent pieces (`2`) you can **capture**.

A piece moves **horizontally and vertically** any number of spaces **until it encounters an opponent piece** and captures it by replacing its position.

Find and return **the optimal (x, y) position** where you should place your piece to **maximize captures**. If multiple positions exist, return **any valid one**.

### **Constraints:**

- `2 ≤ n ≤ 10`
- **At least one `1` and one `2` exist on the board.**

### **Example:**

#### **Input:**

python

CopyEdit

`board = [     [1, 0, 2, 0],     [0, 0, 0, 2],     [2, 0, 1, 0],     [0, 2, 0, 0] ]`

#### **Output:**

python

CopyEdit

`(1, 1)`

#### **Explanation:**

Placing a `1` at `(1,1)` allows capturing **multiple opponent pieces**.

---

## **3. Generate Phone Numbers with Constraints**

**Difficulty: Medium**

### **Problem Statement:**

You need to generate **all possible phone numbers** of length `n`, ensuring:

- **Three specific digits** cannot be used in the number.
- **No two consecutive digits** can be the same.
- If a number contains `4`, it must **start with 4**.

### **Constraints:**

- `1 ≤ n ≤ 10`
- Three restricted digits are given as input.

### **Example:**

#### **Input:**

python

CopyEdit

`n = 3 restricted_digits = {2, 5, 7}`

#### **Output:**

python

CopyEdit

`["101", "103", "104", "106", "108", "109", ...]`

---

## **4. Find the Next Leap Day**

**Difficulty: Easy**

### **Problem Statement:**

Assume:

- Every month has **30 days**.
- **Leap years follow:**
    - `(year % 40 == 0)` → Leap year
    - `(year % 200 == 0)` → NOT a leap year
    - `(year % 1000 == 0)` → Leap year

Given a date in **MM/DD/YYYY** format, find the **next leap day (02/31/YYYY)**.

### **Example:**

#### **Input:**

python

CopyEdit

`date = "03/15/1960"`

#### **Output:**

python

CopyEdit

`"02/31/2000"`

---

## **5. Print a Matrix in Spiral Order**

**Difficulty: Medium**

### **Problem Statement:**

Given an `n x m` matrix, return its elements in **spiral order**.

### **Example:**

#### **Input:**

python

CopyEdit

`matrix = [     [1, 2, 3],     [4, 5, 6],     [7, 8, 9] ]`

#### **Output:**

python

CopyEdit

`[1, 2, 3, 6, 9, 8, 7, 4, 5]`

---

## **6. Unique Product Subsets in a Number**

**Difficulty: Hard**

### **Problem Statement:**

Given a number as a string, generate all **non-empty subsets** of its digits and check if any two subsets have the **same product**.

If **two subsets exist with the same product**, return `False`. Otherwise, return `True`.

### **Example:**

#### **Input:**

python

CopyEdit

`num = "345"`

#### **Output:**

python

CopyEdit

`True`

#### **Explanation:**

- Possible subsets: `{3, 4, 5, 34, 45, 35, 345}`
- Products: `{3, 4, 5, 12, 20, 15, 60}` → All unique

#### **Input:**

python

CopyEdit

`num = "3426"`

#### **Output:**

python

CopyEdit

`False`

#### **Explanation:**

- `{3, 4, 2, 6, 34, 42, 26, ...}`
- Product `{3, 4, 2, 6, 12, 8, 12, ...}` → `12` appears twice

---

## **7. Generate Perfect Ordering Strings of Length `N`**

**Difficulty: Medium**

### **Problem Statement:**

A string is called **"perfectly ordered"** if all characters are **in strictly increasing order** (`a < c < h < q`).

Given an integer `N`, print all **perfectly ordered strings** of length `N`.

### **Example:**

#### **Input:**

python

CopyEdit

`N = 2`

#### **Output:**

python

CopyEdit

`["ab", "ac", "ad", ..., "az", "bc", "bd", ..., "bz", "cd", ..., "yz"]`

---

## **8. Personality Test (Behavioral MCQ Round)**

This round consists of **multiple-choice behavioral questions**, evaluating **your personality, decision-making, and work style**.

**Example Questions:**  
📌 _How do you handle conflict in a team setting?_  
📌 _What would you do if a team member wasn’t completing their work on time?_  
📌 _Do you prefer structured guidelines or flexible problem-solving?_

📢 This is **not an elimination round**, but **answer honestly and consistently** to reflect the best version of yourself!

---

## **How to Practice These Questions?**

🔥 **LeetCode Problems Related to These Topics:**

- **Backtracking & Permutations:** 🔗 LeetCode 46 - Permutations
- **Matrix Traversal:** [🔗 LeetCode 54 - Spiral Matrix](https://leetcode.com/problems/spiral-matrix/)
- **Number Subsets & Products:** 🔗 LeetCode 1980 - Find Unique Binary String
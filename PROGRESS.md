# 📊 Daily Progress Log

> **Tracking the 250-Day Grind to Google.**

| Day | Date | Focus Area | Problems Solved | Key Concepts/Takeaways | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **01** | *[Insert Date]* | Java Memory & Arrays | 1. [LeetCode 1929](Day01/Concatenation.java)<br>2. [LeetCode 1920](Day01/BuildArray.java) | Stack vs Heap, String Pool, Array Allocation | ✅ Done |
| **02** | - | - | - | - | ⏳ Pending |
| **03** | - | - | - | - | ⏳ Pending |

---

## 📝 Detailed Notes

### **Day 01: The Foundation**
**Focus:** Understanding how Java handles memory to write efficient code.

**1. Stack vs Heap**
* **Stack:** Fast access, stores primitive variables (`int`, `char`) and reference variables. Cleared when methods return.
* **Heap:** Stores Objects (`new int[]`, `new Student()`). Managed by Garbage Collector.
* **Insight:** `int[] arr = new int[5]` -> `arr` is in Stack, `[0,0,0,0,0]` is in Heap.

**2. The String Pool**
* Strings are immutable in Java.
* `String s1 = "Hi"` checks the pool first (saves memory).
* `String s2 = new String("Hi")` forces a new object in Heap (wasteful).

**3. LeetCode Analysis**
* **LC 1929:** Solved using a single loop $O(n)$.
* **LC 1920:** Solved using direct indexing.  

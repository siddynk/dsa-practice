<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=header&text=DSA%20Practice%20%F0%9F%92%A1&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=38" width="100%"/>

# 💡 LeetCode Solutions
### by [Sid Nayak](https://github.com/siddynk)

[![LeetCode](https://img.shields.io/badge/LeetCode-sidspams-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/sidspams/)
[![Language](https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://github.com/siddynk/dsa-practice)
[![MySQL](https://img.shields.io/badge/Database-MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://github.com/siddynk/dsa-practice)
[![Problems](https://img.shields.io/badge/Solved-119%2B-success?style=for-the-badge)](https://leetcode.com/u/sidspams/)

</div>

---

## 📊 Progress Tracker

| Difficulty | Solved | Language |
|---|---|---|
| 🟢 Easy | ✅ Solved | Java · MySQL |
| 🟡 Medium | ✅ Solved | Java |
| 🔴 Hard | ✅ Solved | Java |
| **Total** | **119+** | **Java · MySQL** |

---

## 🧠 Topics Covered

<div align="center">

| Topic | Problems | Level |
|---|---|---|
| 📦 Array | 53+ | Fundamental |
| 🔤 String | 31+ | Fundamental |
| 👆 Two Pointers | 18+ | Fundamental |
| 🗂 Hash Table | 21+ | Intermediate |
| ➗ Math | 14+ | Intermediate |
| 🌲 Depth-First Search | 13+ | Intermediate |
| 🧮 Dynamic Programming | 24+ | Advanced |
| ⚖️ Divide & Conquer | 6+ | Advanced |
| 📚 Monotonic Stack | 4+ | Advanced |
| 🗄 SQL / MySQL | 7+ | Database |

</div>

---

## 📁 Repository Structure

```
dsa-practice/
│
├── 📂 Easy/
│   ├── two-sum.java
│   ├── palindrome-number.java
│   ├── valid-parentheses.java
│   └── ...
│
├── 📂 Medium/
│   ├── longest-substring-without-repeating.java
│   ├── add-two-numbers.java
│   ├── container-with-most-water.java
│   └── ...
│
├── 📂 Hard/
│   ├── median-of-two-sorted-arrays.java
│   └── ...
│
└── 📂 SQL/
    ├── second-highest-salary.sql
    ├── rank-scores.sql
    └── ...
```

---

## 🗂 Topic-wise Index

### 📦 Arrays
| # | Problem | Difficulty | Solution |
|---|---|---|---|
| 1 | Two Sum | 🟢 Easy | [View](./Easy/two-sum.java) |
| 11 | Container With Most Water | 🟡 Medium | [View](./Medium/container-with-most-water.java) |
| 53 | Maximum Subarray | 🟡 Medium | [View](./Medium/maximum-subarray.java) |

### 🔤 Strings
| # | Problem | Difficulty | Solution |
|---|---|---|---|
| 3 | Longest Substring Without Repeating | 🟡 Medium | [View](./Medium/longest-substring-without-repeating.java) |
| 9 | Palindrome Number | 🟢 Easy | [View](./Easy/palindrome-number.java) |
| 20 | Valid Parentheses | 🟢 Easy | [View](./Easy/valid-parentheses.java) |

### 🧮 Dynamic Programming
| # | Problem | Difficulty | Solution |
|---|---|---|---|
| 70 | Climbing Stairs | 🟢 Easy | [View](./Easy/climbing-stairs.java) |
| 198 | House Robber | 🟡 Medium | [View](./Medium/house-robber.java) |
| 322 | Coin Change | 🟡 Medium | [View](./Medium/coin-change.java) |

### 🗄 SQL
| # | Problem | Difficulty | Solution |
|---|---|---|---|
| 176 | Second Highest Salary | 🟡 Medium | [View](./SQL/second-highest-salary.sql) |
| 177 | Nth Highest Salary | 🟡 Medium | [View](./SQL/nth-highest-salary.sql) |
| 178 | Rank Scores | 🟡 Medium | [View](./SQL/rank-scores.sql) |

> ⚠️ **Note:** The tables above show sample entries. Full solutions are inside the folders above — one file per problem, named by problem title.

---

## 💡 My Approach

Every solution file follows this structure:

```java
/**
 * Problem: Two Sum (LeetCode #1)
 * Difficulty: Easy
 * Topic: Array, Hash Table
 *
 * Approach:
 * Use a HashMap to store each number and its index as we iterate.
 * For each element, check if (target - current) already exists in the map.
 * If yes, we found our pair. Time: O(n), Space: O(n).
 */
class Solution {
    public int[] twoSum(int[] nums, int target) {
        Map<Integer, Integer> map = new HashMap<>();
        for (int i = 0; i < nums.length; i++) {
            int complement = target - nums[i];
            if (map.containsKey(complement)) {
                return new int[]{map.get(complement), i};
            }
            map.put(nums[i], i);
        }
        return new int[]{};
    }
}
```

---

## 🏆 Milestones

- [x] 🎯 10 problems solved
- [x] 🎯 50 problems solved
- [x] 🎯 100 problems solved
- [ ] 🎯 150 problems solved
- [ ] 🎯 200 problems solved
- [ ] 🎯 300 problems solved

---

## 🔗 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-siddynk-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/siddynk)
[![LeetCode](https://img.shields.io/badge/LeetCode-sidspams-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/sidspams/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nayak--sid-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nayak-sid)

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>

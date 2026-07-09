<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=DSA%20Practice&fontSize=60&animation=twinkling&fontAlignY=35&desc=Data%20Structures%20%26%20Algorithms%20Solutions%20by%20Sid%20Nayak&descAlignY=55&descSize=18)

# 💡 Data Structures & Algorithms Solutions by Sid Nayak

[![LeetCode](https://img.shields.io/badge/LeetCode-sidspams-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/sidspams/)
[![Languages](https://img.shields.io/badge/Language-Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)](#)
[![Database](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](#)
[![Solved](https://img.shields.io/badge/Problems%20Solved-119%2B-2CA5E0?style=for-the-badge&logo=checkmarx&logoColor=white)](#)

*A structured, multi-platform collection of DSA problem-solving — clean code, clear patterns, consistent practice.*

</div>

---

## 📊 Progress Tracker

| Platform | Difficulty Levels | Status | Languages |
|---|---|---|---|
| 🟧 **LeetCode** | Easy / Medium / Hard | ✅ Tracked | Java, MySQL |
| 🟩 **GeeksforGeeks** | School / Basic / Easy / Medium / Hard | ✅ Tracked | Java |

---

## 🗂️ Repository Structure

```
dsa-practice/
├── .github/
│   └── workflows/
│       └── (CI automation configs)
│
├── LeetCode/
│   ├── Easy/
│   ├── Medium/
│   └── Hard/
│
└── GeeksforGeeks/
    ├── School/
    ├── Basic/
    ├── Easy/
    ├── Medium/
    └── Hard/
```

---

## 📚 Topic-Wise Index

### 🔢 Arrays

| # | Problem | Difficulty | Platform | Solution |
|---|---|---|---|---|
| 1 | Two Sum | 🟢 Easy | LeetCode | [View](./LeetCode/Easy/two-sum/) |
| 2 | Maximum Subarray | 🟡 Medium | LeetCode | [View](./LeetCode/Medium/maximum-subarray/) |
| 3 | Best Time to Buy and Sell Stock | 🟢 Easy | LeetCode | [View](./LeetCode/Easy/best-time-to-buy-and-sell-stock/) |
| 4 | Trapping Rain Water | 🔴 Hard | LeetCode | [View](./LeetCode/Hard/trapping-rain-water/) |
| 5 | Kadane's Algorithm | 🟡 Medium | GeeksforGeeks | [View](./GeeksforGeeks/Medium/kadanes-algorithm/) |

### 🔤 Strings

| # | Problem | Difficulty | Platform | Solution |
|---|---|---|---|---|
| 1 | Valid Anagram | 🟢 Easy | LeetCode | [View](./LeetCode/Easy/valid-anagram/) |
| 2 | Longest Substring Without Repeating Characters | 🟡 Medium | LeetCode | [View](./LeetCode/Medium/longest-substring-without-repeating-characters/) |
| 3 | Minimum Window Substring | 🔴 Hard | LeetCode | [View](./LeetCode/Hard/minimum-window-substring/) |
| 4 | Palindrome Check | ⚪ Basic | GeeksforGeeks | [View](./GeeksforGeeks/Basic/palindrome-check/) |

### 🧮 Dynamic Programming

| # | Problem | Difficulty | Platform | Solution |
|---|---|---|---|---|
| 1 | Climbing Stairs | 🟢 Easy | LeetCode | [View](./LeetCode/Easy/climbing-stairs/) |
| 2 | Coin Change | 🟡 Medium | LeetCode | [View](./LeetCode/Medium/coin-change/) |
| 3 | Longest Common Subsequence | 🟡 Medium | LeetCode | [View](./LeetCode/Medium/longest-common-subsequence/) |
| 4 | Edit Distance | 🔴 Hard | LeetCode | [View](./LeetCode/Hard/edit-distance/) |
| 5 | 0/1 Knapsack | 🟡 Medium | GeeksforGeeks | [View](./GeeksforGeeks/Medium/0-1-knapsack/) |

---

## 🧩 My Approach — Solution Template

Every solution follows a consistent, documented format for clarity and future reference:

```java
/**
 * Problem: Two Sum
 * Platform: LeetCode | Difficulty: Easy
 * Link: https://leetcode.com/problems/two-sum/
 *
 * Approach:
 * Use a HashMap to store each number's complement (target - num) while
 * iterating through the array once. For every element, check if its
 * complement already exists in the map — if so, we've found our pair.
 *
 * Time Complexity:  O(n)  — single pass through the array
 * Space Complexity: O(n)  — HashMap storing up to n elements
 */
import java.util.HashMap;
import java.util.Map;

class Solution {
    public int[] twoSum(int[] nums, int target) {
        Map<Integer, Integer> seen = new HashMap<>();

        for (int i = 0; i < nums.length; i++) {
            int complement = target - nums[i];

            if (seen.containsKey(complement)) {
                return new int[] { seen.get(complement), i };
            }

            seen.put(nums[i], i);
        }

        throw new IllegalArgumentException("No two sum solution exists");
    }
}
```

---

## 🏆 Milestones

Tracking progress toward 300 problems solved:

- [x] 🎯 25 Problems Solved
- [x] 🎯 50 Problems Solved
- [x] 🎯 100 Problems Solved
- [x] 🎯 119+ Problems Solved *(current)*
- [ ] 🎯 150 Problems Solved
- [ ] 🎯 200 Problems Solved
- [ ] 🎯 250 Problems Solved
- [ ] 🎯 300 Problems Solved

---

<div align="center">

## 🤝 Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-siddynk-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/siddynk)
[![LeetCode](https://img.shields.io/badge/LeetCode-sidspams-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/sidspams/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nayak--sid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nayak-sid)

### ⭐ If this repository helped you, consider giving it a star!

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=footer&animation=twinkling)

</div>

# HackerRank 3rd Sem Algorithm Portfolio

## Student Details

- **Student Name:** Gnanesh Gowda D P
- **USN / Student ID:** R25EF089
- **Semester:** 3rd Semester
- **Date:** October 1, 2026
- **Programming Language:** C++

## Profiles

- **HackerRank Profile:** https://www.hackerrank.com/profile/gnaneshgowdadp27
- **GitHub Repository:** https://github.com/gnaneshappu/HackerRank-3rdSem-Algorithm-Portfolio.git

## Introduction

This repository contains my solutions for the HackerRank 3rd Semester Algorithm activity. The portfolio demonstrates my understanding of arrays, sorting, searching, greedy algorithms, and algorithmic complexity analysis using C++.

## Problems Completed

| No. | Problem | Topic | Time Complexity | Auxiliary Space |
|---|---|---|---|---|
| 1 | Mini-Max Sum | Arrays / Implementation | O(N) | O(1) |
| 2 | Birthday Cake Candles | Arrays / Counting | O(N) | O(1) |
| 3 | Insertion Sort Part 1 | Sorting | O(N) | O(1) |
| 4 | Binary Search | Searching | O(log N) | O(1) |
| 5 | Mark and Toys | Greedy / Sorting | O(N log N) | O(1) excluding sorting implementation |

## 1. Mini-Max Sum

### Approach
Traverse the array once while calculating the total sum, minimum value, and maximum value. The minimum sum is obtained by excluding the maximum value, and the maximum sum is obtained by excluding the minimum value.

### Complexity
- **Time:** O(N)
- **Auxiliary Space:** O(1)

### Folder
`01-Mini-Max-Sum/solution.cpp`

## 2. Birthday Cake Candles

### Approach
Traverse the array and keep track of the maximum candle height and how many times that maximum occurs.

### Complexity
- **Time:** O(N)
- **Auxiliary Space:** O(1)

### Folder
`02-Birthday-Cake-Candles/solution.cpp`

## 3. Insertion Sort Part 1

### Approach
Store the last element and shift larger elements in the sorted portion one position to the right until the correct position for the stored element is found.

### Complexity
- **Time:** O(N)
- **Auxiliary Space:** O(1)

### Folder
`03-Insertion-Sort-Part-1/solution.cpp`

## 4. Binary Search

### Approach
Binary search works on a sorted array. The middle element is compared with the target. Depending on the comparison, either the left or right half is discarded.

### Complexity
- **Time:** O(log N)
- **Auxiliary Space:** O(1)

### Folder
`04-Binary-Search/solution.cpp`

## 5. Mark and Toys

### Approach
Sort the toy prices in ascending order and purchase the cheapest toys while the available budget allows.

### Complexity
- **Time:** O(N log N)
- **Auxiliary Space:** O(1) auxiliary space excluding the sorting implementation.

### Folder
`05-Mark-and-Toys/solution.cpp`

## Alternative Approaches

Different approaches can be used depending on the problem. For example, Mini-Max Sum can be solved by sorting the array, but a single traversal is more efficient because it avoids the O(N log N) sorting step. Binary Search is preferable to linear search when the array is sorted because it reduces the search space by half at every step.

## Learning Outcomes

Through these problems, I learned how to implement and analyse fundamental algorithms involving arrays, sorting, searching, and greedy strategies. I also learned how to evaluate algorithms using Big-O notation and organize coding solutions using GitHub.

## Evidence

Screenshots of accepted HackerRank submissions and profile/badge evidence are included in the activity submission/report.

## Conclusion

This portfolio demonstrates my implementation of five fundamental algorithmic problems using C++. It also demonstrates my understanding of algorithm efficiency, complexity analysis, Git, GitHub, and structured documentation.
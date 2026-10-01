# HackerRank 3rd Sem Algorithm Portfolio

## Student Information

- **Name:** Gnanesh Gowda D P
- **USN / Student ID:** R25EF089
- **Semester:** 3rd Semester
- **Date:** October 1, 2026
- **Programming Language:** C++
- **HackerRank Profile:** https://www.hackerrank.com/profile/gnaneshgowdadp27
- **GitHub Repository:** https://github.com/gnaneshappu

---

## About This Portfolio

This repository contains my solutions to five mandatory algorithmic
problems completed as part of the 3rd Semester Computer Science and
Engineering algorithm activity.

The problems cover arrays, sorting, searching, and greedy algorithms.
Each solution includes an appropriate algorithm and complexity analysis.

---

## Problems Completed

| No. | Problem | Topic | Time Complexity | Auxiliary Space |
|---|---|---|---|---|
| 1 | Mini-Max Sum | Arrays | O(N) | O(1) |
| 2 | Birthday Cake Candles | Arrays / Counting | O(N) | O(1) |
| 3 | Insertion Sort Part 1 | Sorting | O(N) | O(1) |
| 4 | Binary Search | Searching | O(log N) | O(1) |
| 5 | Mark and Toys | Greedy / Sorting | O(N log N) | O(1) |

---

# 1. Mini-Max Sum

### Problem Summary

Given five positive integers, calculate the minimum and maximum values
that can be obtained by summing exactly four of the five integers.

### Approach

Traverse the array once and calculate:

- Total sum
- Minimum element
- Maximum element

The minimum sum is:

`Total Sum - Maximum`

The maximum sum is:

`Total Sum - Minimum`

### Complexity

- **Time:** O(N)
- **Auxiliary Space:** O(1)

### HackerRank

https://www.hackerrank.com/challenges/mini-max-sum/problem

### Solution

[View Solution](01-Mini-Max-Sum/solution.cpp)

---

# 2. Birthday Cake Candles

### Problem Summary

Given the heights of candles, find how many candles have the maximum
height.

### Approach

Traverse the array while maintaining the maximum candle height and the
number of candles having that height.

Whenever a larger height is found, update the maximum and reset the count.
If the same maximum occurs again, increase the count.

### Complexity

- **Time:** O(N)
- **Auxiliary Space:** O(1)

### HackerRank

https://www.hackerrank.com/challenges/birthday-cake-candles/problem

### Solution

[View Solution](02-Birthday-Cake-Candles/solution.cpp)

---

# 3. Insertion Sort Part 1

### Problem Summary

Insert the last element of an array into its correct position in the
already sorted portion of the array.

### Approach

Store the last element as the value to insert.

Compare it with the elements before it. Larger elements are shifted one
position to the right until the correct position is found.

### Complexity

- **Time:** O(N)
- **Auxiliary Space:** O(1)

### HackerRank

https://www.hackerrank.com/challenges/insertionsort1/problem

### Solution

[View Solution](03-Insertion-Sort-Part-1/solution.cpp)

---

# 4. Binary Search

### Problem Summary

Search for a target value in a sorted array and return its index.

### Approach

Binary search repeatedly divides the search range into two halves.

If the middle element is equal to the target, its index is returned.

If the middle element is smaller than the target, the right half is
searched. Otherwise, the left half is searched.

### Complexity

- **Time:** O(log N)
- **Auxiliary Space:** O(1)

### HackerRank

https://www.hackerrank.com/challenges/tutorial-intro/problem

### Solution

[View Solution](04-Binary-Search/solution.cpp)

---

# 5. Mark and Toys

### Problem Summary

Given prices of toys and a fixed budget, determine the maximum number
of toys that can be purchased.

### Approach

Sort the toy prices in ascending order.

Starting with the cheapest toy, keep purchasing toys while the total cost
does not exceed the available budget.

This greedy approach maximizes the number of toys purchased.

### Complexity

- **Time:** O(N log N)
- **Auxiliary Space:** O(1) auxiliary space apart from the sorting
  implementation.

### HackerRank

https://www.hackerrank.com/challenges/mark-and-toys/problem

### Solution

[View Solution](05-Mark-and-Toys/solution.cpp)

---

# Algorithmic Techniques Learned

Through these five problems, I practiced several fundamental algorithmic
techniques.

Mini-Max Sum and Birthday Cake Candles helped me understand array
traversal, minimum and maximum tracking, and counting.

Insertion Sort Part 1 demonstrated how elements can be shifted to insert
a value into its correct position.

Binary Search showed how a sorted array can be searched efficiently by
repeatedly dividing the search space into two halves.

Mark and Toys introduced the greedy approach, where sorting the prices
allows the cheapest available toys to be selected first.

These problems also helped me understand the importance of analysing
Time Complexity and Auxiliary Space Complexity before selecting an
algorithm.

---

# Alternative Approaches

| Problem | Alternative Approach |
|---|---|
| Mini-Max Sum | Sort the array and sum the first/last four elements |
| Birthday Cake Candles | Sort the array and count occurrences of the largest element |
| Insertion Sort Part 1 | Use a library sorting algorithm, although it does not demonstrate the required insertion operation |
| Binary Search | Linear search with O(N) time |
| Mark and Toys | Try combinations of toys, which is inefficient compared with the greedy approach |

---

# Evidence

The project includes evidence of completed HackerRank challenges and
accepted submissions.

Evidence will include:

- Mini-Max Sum accepted submission
- Birthday Cake Candles accepted submission
- Insertion Sort Part 1 accepted submission
- Binary Search accepted submission
- Mark and Toys accepted submission
- HackerRank profile/badge evidence, if applicable

---

# Conclusion

This portfolio demonstrates the implementation of five fundamental
algorithmic problems using C++. The problems provided practical
experience with arrays, sorting, searching, and greedy algorithms.

The activity also helped me understand how algorithm selection affects
program efficiency and how Time Complexity and Auxiliary Space Complexity
can be used to compare different approaches.

The solutions are organized into separate folders and documented so that
they can be easily reviewed as part of my academic and coding portfolio.
LeetCode Activity 3 – Java Solutions

Overview

This repository contains solutions to five LeetCode problems implemented using Java as part of Activity 3. The problems cover important Data Structures and Algorithms (DSA) concepts, including sorting, frequency counting, heaps, graph traversal, and interval merging.

The objective of this activity is to strengthen Java programming skills, understand algorithmic techniques, and develop efficient solutions to common coding problems.

Problems Covered

1. Sort an Array (LeetCode 912)

Description: Given an integer array, sort the array in ascending order without using built-in sorting functions. The solution uses the Merge Sort algorithm to achieve efficient sorting.

Example:

- Input: "nums = [5,2,3,1]"
- Output: "[1,2,3,5]"

Algorithm: Merge Sort

Time Complexity: O(n log n)

Space Complexity: O(n)

2. Top K Frequent Elements (LeetCode 347)

Description: Given an integer array and an integer "k", return the "k" most frequent elements. A HashMap is used to count element frequencies, and a Priority Queue is used to retrieve the most frequent elements.

Example:

- Input: "nums = [1,1,1,2,2,3], k = 2"
- Output: "[1,2]"

Concepts: HashMap, Priority Queue, Frequency Counting

3. Find Median from Data Stream (LeetCode 295)

Description: Design a "MedianFinder" class that supports adding numbers to a data stream and finding the median of all numbers added so far. Two heaps are used to maintain the lower and upper halves of the numbers.

Example:

- Add "1" and "2" → Median: "1.5"
- Add "3" → Median: "2.0"

Concepts: Two Heaps, Priority Queue, Data Stream Processing

4. Course Schedule (LeetCode 207)

Description: Given the total number of courses and a list of prerequisite pairs, determine whether all courses can be completed. The solution represents courses as a directed graph and uses Breadth-First Search (BFS) with topological sorting to detect cycles.

Example 1:

- Input: "numCourses = 2, prerequisites = [[1,0]]"
- Output: "true"

Example 2:

- Input: "numCourses = 2, prerequisites = [[1,0],[0,1]]"
- Output: "false"

Concepts: Graphs, BFS, Topological Sorting, Cycle Detection

5. Merge Intervals (LeetCode 56)

Description: Given an array of intervals, merge all overlapping intervals and return an array of non-overlapping intervals. The solution sorts intervals by their starting values and combines intervals that overlap.

Example:

- Input: "intervals = [[1,3],[2,6],[8,10],[15,18]]"
- Output: "[[1,6],[8,10],[15,18]]"

Concepts: Arrays, Sorting, Interval Merging

Technologies Used

- Programming Language: Java
- Coding Platform: LeetCode
- Core Topics: Data Structures and Algorithms
- Data Structures: Arrays, HashMap, Priority Queue, Heaps, Graphs

Learning Outcomes

- Improved understanding of Java programming and algorithm implementation.
- Learned to apply sorting algorithms efficiently.
- Practiced frequency counting using HashMap and Priority Queue.
- Understood median calculation using two heaps.
- Learned graph traversal and topological sorting for prerequisite problems.
- Practiced merging overlapping intervals.
- Improved logical thinking, problem-solving, and algorithm analysis skills.

Conclusion

This activity provided practical experience in solving algorithmic problems using Java. It strengthened my understanding of fundamental DSA concepts and helped me improve my coding efficiency and problem-solving abilities.

---

Language: Java
Platform: LeetCode
Activity: 3 – DSA Problem Solving

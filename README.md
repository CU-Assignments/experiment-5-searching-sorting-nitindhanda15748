[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/oFiD4H68)
# 22BCS_IOT-634-A-Exp-5_AP

1. Merge Sorted Array	--	https://leetcode.com/problems/merge-sorted-array/
2. First Bad Version	--	https://leetcode.com/problems/first-bad-version/
3. Sort Colors	--	https://leetcode.com/problems/sort-colors/
4. Top K frequent elements	--	https://leetcode.com/problems/top-k-frequent-elements/
5. Kth Largest element in an array	--	https://leetcode.com/problems/kth-largest-element-in-an-array/
6. Find Peak Element	--	https://leetcode.com/problems/find-peak-element/
7. Search For a range	--	https://leetcode.com/problems/search-for-a-range/
8. Merge Intervals	--	https://leetcode.com/problems/merge-intervals/
9. Search in Rotated Sorted Array	--	https://leetcode.com/problems/search-in-rotated-sorted-array/
10. Search a 2D Matrix II	--	https://leetcode.com/problems/search-a-2d-matrix-ii/
11. Wiggle Sort 2	--	https://leetcode.com/problems/wiggle-sort-2/
12. Kth smallest element in a sorted matrix	--	https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/
13. Median of Two Sorted Arrays	--	https://leetcode.com/problems/median-of-two-sorted-arrays/

Sorting and Searching Problems - AP Assignment

Description

This repository contains solutions to five fundamental sorting and searching problems in Python. The problems involve merging sorted arrays, in-place sorting, finding the kth largest element, searching in rotated sorted arrays, and finding the median of two sorted arrays.

Problems and Solutions

1. Merge Sorted Array

Problem: Given two sorted integer arrays nums1 and nums2, merge them into a single sorted array in-place.

Solution: Utilizes a two-pointer approach, merging from the back to avoid extra space usage.

Time Complexity: O(m + n)

2. Sort Colors

Problem: Given an array nums with integers 0, 1, and 2 representing colors, sort them in-place without using the built-in sort function.

Solution: Implements the Dutch National Flag algorithm for an efficient in-place sort.

Time Complexity: O(n)

3. Kth Largest Element

Problem: Given an integer array nums and an integer k, return the kth largest element.

Solution: Uses a min-heap of size k or quickselect partitioning for O(n) average time complexity.

Time Complexity: O(n) (quickselect), O(n log k) (heap)

4. Search in Rotated Sorted Array

Problem: Given a rotated sorted array and a target integer, return its index or -1 if not found.

Solution: Implements binary search with modifications to handle rotation.

Time Complexity: O(log n)

5. Median of Two Sorted Arrays

Problem: Given two sorted arrays nums1 and nums2, return their median.

Solution: Uses binary search on the smaller array to partition both arrays optimally.

Time Complexity: O(log (m+n))

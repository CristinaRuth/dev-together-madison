# Coding Problems

Pair junior/senior developers to discuss and practice working through any of the coding problems below.

# Easy

## Problem #63 [Easy]
This problem was asked by Microsoft.

Given a 2D matrix of characters and a target word, write a function that returns whether the word can be found in the matrix by going left-to-right, or up-to-down.

For example, given the following matrix:

```
[['F', 'A', 'C', 'I'],
 ['O', 'B', 'Q', 'P'],
 ['A', 'N', 'O', 'B'],
 ['M', 'A', 'S', 'S']]
```

and the target word `FOAM`, you should return true, since it's the leftmost column. Similarly, given the target word `MASS`, you should return true, since it's the last row.

## Problem #47 [Easy]
This problem was asked by Facebook.

Given a array of numbers representing the stock prices of a company in chronological order, write a function that calculates the maximum profit you could have made from buying and selling that stock once. You must buy before you can sell it.

For example, given [9, 11, 8, 5, 7, 10], you should return 5, since you could buy the stock at 5 dollars and sell it at 10 dollars.

## Problem #55 [Easy]
This problem was asked by Microsoft.

Implement a URL shortener with the following methods:
* `shorten(url)`, which shortens the url into a six-character alphanumeric string, such as zLg6wl.
* `restore(short)`, which expands the shortened string into the original url. If no such shortened string exists, return null.

Hint: What if we enter the same URL twice?

# Medium

## Problem #36 [Medium]
This problem was asked by Dropbox.

Given the root to a binary search tree, find the second largest node in the tree.

## Problem #56 [Medium]
This problem was asked by Google.

Given an undirected graph represented as an adjacency matrix and an integer k, write a function to determine whether each vertex in the graph can be colored such that no two adjacent vertices share the same color using at most k colors.

## Problem #57 [Medium]
This problem was asked by Amazon.

Given a string s and an integer k, break up the string into multiple lines such that each line has a length of k or less. You must break it up so that words don't break across lines. Each line has to have the maximum possible amount of words. If there's no way to break the text up, then return null.

You can assume that there are no spaces at the ends of the string and that there is exactly one space between each word.

For example, given the string `the quick brown fox jumps over the lazy dog` and `k = 10`, you should return: `["the quick", "brown fox", "jumps over", "the lazy", "dog"]`. No string in the list has a length of more than 10.

## Problem #58 [Medium]
This problem was asked by Amazon.

An sorted array of integers was rotated an unknown number of times.

Given such an array, find the index of the element in the array in faster than linear time. If the element doesn't exist in the array, return null.

For example, given the array `[13, 18, 25, 2, 8, 10]` and the element 8, return 4 (the index of 8 in the array).

You can assume all the integers in the array are unique.

## Problem #53 [Medium]
This problem was asked by Apple.

Implement a queue using two stacks. Recall that a queue is a FIFO (first-in, first-out) data structure with the following methods: enqueue, which inserts an element into the queue, and dequeue, which removes it.

# Hard
## Problem #52 [Hard]
This problem was asked by Google.

Implement an LRU (Least Recently Used) cache. It should be able to be initialized with a cache size n, and contain the following methods:

* `set(key, value)`: sets key to value. If there are already n items in the cache and we are adding a new item, then it should also remove the least recently used item.
* `get(key):` gets the value at key. If no such key exists, return null.

Each operation should run in O(1) time.

## Problem #54 [Hard]
This problem was asked by Dropbox.

Sudoku is a puzzle where you're given a partially-filled 9 by 9 grid with digits. The objective is to fill the grid with the constraint that every row, column, and box (3 by 3 subgrid) must contain all of the digits from 1 to 9.

Implement an efficient sudoku solver.

## Problem #59 [Hard]
This problem was asked by Google.

Implement a file syncing algorithm for two computers over a low-bandwidth network. What if we know the files in the two computers are mostly the same?


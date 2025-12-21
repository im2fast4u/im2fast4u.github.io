---
title: "Post: Quicksort"
date: 2025-12-21
---

Just like binary search, quicksort is a very easy algorithm - but it is used to sort a list. You will also find out than there is another algorithm, selection sort, that is also used to sort a list. I will show you how it is slower, and how quicksort is more efficient. There are a lot more sorting algorithms for sorting a list such as merge sort, but they won't be included here. Let's start with selection sort.

To sort an array with selection sort, you have to choose the smallest number in the unsorted array. You swap that number with the first number in the array. That number is in the correct spot. Then, you choose the second smallest number and replace it with the second number in your array. You keep repeating that until all the numbers are in the correct place. That is selection sort. However, quicksort is much faster than selection sort, and that's what what this whole post is about.

```python
def quicksort(array):
    if len(array) < 2:
        return array
    else:
        pivot = array[0]
        less = [i for i in array[1:] if i <= pivot]

        greater = [i for i in array[1:] if i > pivot]

        return quicksort(less) + [pivot] + quicksort(greater)
```

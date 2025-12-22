---
title: "Post: Quicksort"
date: 2025-12-21
---

Just like binary search, quicksort is a very easy algorithm - but it is used to sort a list. You will also find out that there is another algorithm, selection sort, that is also used to sort a list. I will show you how it is slower, and how quicksort is more efficient. There are a lot more sorting algorithms for sorting a list such as merge sort, but they won't be included here. Let's start with selection sort.

To sort an array with selection sort, you have to choose the smallest number in the unsorted array. You swap that number with the first number in the array. That number is in the correct spot. Then, you choose the second smallest number and replace it with the second number in your array. You keep repeating that until all the numbers are in the correct place. That is selection sort. However, quicksort is much faster, and that's what what this whole post is about.

Quiksort uses a method called divide and conquer, so I will explain that before we get straight into quicksort. Divide and coquer is a strategy to solve something by breaking it down into smaller parts, and then adding them back together to find the real answer. Also, divide and conquer is not only used in quicksort. It has a play in many other algorithms such as merge sort.

Let's say we have the list [5, 2, 3]. This is pretty simple. Quiksort usually sorts in ascending order, from smallest to largest. To sort the list, we must choose a pivot. The pivot can be any number, but I will choose 2. Now, we put any numbers smaller than the pivot before it, and any numbers greater than the pivot after it. Therefore, our sorted list is [2, 3, 5].

Now, let's sort a list of four numbers, [3, 1, 7, 4]. I will choose 4 as my pivot. If we follow all the steps and put the larger numbers after the pivot and the smaller numbers before it, we get [3, 1, 4, 7]. That still isn't sorted yet. We got two sub-arrays, [3, 1] and [7]. That means we must use quicksort again on the 3 and 1 (the second sub-array is already sorted). That is called recursion. It is when a function calls itself - we had to use quicksort a second time. Our final sorted list is [1, 3, 4, 7].

I showed you how to use two different algorithms for sorting a list. I also showed you how to use divide and conquer, as well as recursion. We didn't sort an array of five using quicksort - but if you can solve an array four, you can solve an array of five, six, and so on. Quicksort uses the same method for any list. You can now see how quicksort is much faster than selection sort. I will also leave the code for quicksort in Python below, in case you want to see. I hope you enjoyed reading this post!

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
*The Quicksort Function Above Uses Recursion to Sort the Sub-Arrays (The Function Calls Itself)*

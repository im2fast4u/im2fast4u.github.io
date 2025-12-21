---
title: "Post: Quicksort"
date: 2025-12-21
---

Just like binary search, quicksort is a very easy algorithm - but it is used to sort a list. You will also find out than there is another algorithm, selection sort, that is also used to sort a list. I will show you how it is slower, and how binary sort is more efficient.

*The code for quicksort will be left at the bottom of the post in Python*

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

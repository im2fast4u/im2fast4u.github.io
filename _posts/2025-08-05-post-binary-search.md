---
title: "Post: Binary Search"
date: 2025-08-05
---

Here I will show you a popular algorithm that can find an item in a list within just a few seconds! This algorithm is called binary search. It helps you with finding an item in a list very fast. Another algorithm, simple search takes way more time since it looks at each item in the list one by one. Now let's get into how binary search works!

For example, let's say I am thinking of a number between 1 and 100, and you have to guess that number in the fewest tries possible. I will tell you if your guess is too high, too low or correct. So, let's say you guess 1, then you guess 2, and so on. That is simple search. It will take you 100 tries to get the answer correct in the worst case. But in binary search, you always guess the number in between the choices.

So, let's say you guess 50 and I say it's too low. That isn't bad even though you got it wrong, because you eliminated half the numbers! All the numbers from 1 to 50 are gone, so you only have 50 numbers left to guess. So, then you take half the remaining numbers and get 75. I say that it is too high but now you only have 25 numbers left to guess!

This algorithm can be used when you are trying to find anything in a list. Suppose you have a dictionary, and you try to find the letter I. You can use binary search for this problem. Go to half of the book. The letter you find is M, which is too high. So, then you flip through half of the book from A to M, and so on.

So now I hope you know what binary search is if you didn't know. You also know how to use binary search in real life situations and how it is faster than simple search. I will leave the finished code for binary search in Python at the bottom of this blog post. I hope you enjoyed learning what binary search is, and thank you for reading!

```python
def binary_search(list, item):
    low = 0
    high = len(list)-1

    while low <= high:
        mid = (low + high) // 2
        guess = list[mid]
        if guess == item:
            return mid
        if guess > item:
            high = mid - 1
        else:
          low = mid + 1
    return None
```
*The Binary Search Function Above Leaves The Index Of The Item In The List And Returns* `None` *If The Item Is Not In The List*

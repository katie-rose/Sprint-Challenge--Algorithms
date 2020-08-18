#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)
The while loop has a runtime complexity of O(n) because it loops O(n) times. Not an ideal way to go about things.

b)
Runtime would be O(n log n). This is due to the loop within a loop, where the outside loop has a runtime complexity of O(n). The inner loop has a runtime complexity of log(n) because the cursor is multiplied by 2 on each iteration and counts up to n.

c)
This would have a runtime complexity of O(n) because the recursion has a linear relationship with the input size. This is because it calls itself no more than once with one base case.

## Exercise II

I would use O(log n) for this approach.

I'll try dropping from a low height to lessen chances it will break and add height (floors) using a binary search. I would then double the floors until an egg breaks and halve until I hit the minimum point where an egg will break.

Given the number of "plenty of eggs", this would result in less broken eggs and allow a chance to test. If you started from the top, it would all be over pretty quick.

#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) untime complexity is `O(n^3)`. The `while` loop runs depending on how big `n^3` is. The code will take exponentially longer to run the igger `n` is



b) Runtime complexity is `O(n)`. The bigger `n` is the longer the code will take to run in a linear scale.


c) Runtime complexity is `O(1)`. The function only checks whether or not bunnies exists. The amount of bunnies does not change how long it takes to run.


## Exercise II
1 Drop the egg from the middle floor. If the return value is "Egg Broke", move to the current floor minus one and try again until return is "Egg Not Broke"
2 If the return value from the middle floor is "Egg Not Broke", move to the current floor plus one until the return value is "Egg Broke"
3 Once the return value is "Egg Broke" move to the current floor minus one and return.

4 Runtime complexities:
- Best case scenario: `O(1)`
- Worst case scenario: `O(log n)`
- Average case: `O(log n)`




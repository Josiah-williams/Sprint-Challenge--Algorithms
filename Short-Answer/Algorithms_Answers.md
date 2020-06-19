#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) runtime complexity is `O(n^3)`. The `while` loop runs depending on how big `n^3` is. The code will take exponentially longer to run the bigger `n` is



b) J theoretically affects the inner loop of this block and the doubling of n how ever we can break this down by identifying that this would be equal to log n, but like in the previous example the outer loop also increases in a linear fashion in regards to n so the two combined would give us 0(n*log n)


c) this would be a runtime of 0(n)


## Exercise II
I think the best solution would be to use a binary search to find the floor that breaks the egg as this would save time, you could start at the middle of the n floor of the building and by using binary if the egg breaks we go down to the bottom half if it doesnt we go up to the top half and repeat. This would quickly allow us to quickly find the the floor 'f'. I also think with using binary the floors would have to be in order from 0 to -1 (n = 0 n = f -1 ).

Taking in to account that we are cutting the amount of floors/time in half i assume the time complexetity would be 0(log n )


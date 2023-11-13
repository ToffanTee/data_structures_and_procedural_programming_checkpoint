# Distinct Sum Algorithm

> This algorthm takes two arrays of numbers and returns the sum of the distinct elements of the arrays.

## Steps

1. Initialize the two arrays 'set1' and 'set2'
2. Create an empty array 'newArray' to store the combined array.
3. Concatenate 'set1' and 'set2' into newArray.
4. Initialize two variables 'arrTotal1' and 'arrTotal2' to '0'.
5. Iterate through 'set1: a'. Iterate through 'set2: i'. If the current element in 'set1' is equal to the current element in 'set2', add the sum of the two elements to 'arrTotal1'.
6. Iterate through 'newArray: a'. Add the current element in newArray to 'arrTotal2'.
7. Calculate the difference sum between 'arrTotal2' and 'arrTotal1'.
8. Output the value of sum.

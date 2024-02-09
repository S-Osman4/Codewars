# Multiples of 3 or 5

📝 **Problem Statement**  
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6, and 9. The sum of these multiples is 23.

Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in.

Additionally, if the number is negative, return 0.

Note: If the number is a multiple of both 3 and 5, only count it once.

Courtesy of [Project Euler - Problem 1](https://projecteuler.net/problem=1)

## Plan


### Understanding the Problem
We need to find the sum of all natural numbers below a given number `n` that are multiples of 3 or 5.

### Input
A positive integer `n`.

### Output
The sum of all multiples of 3 or 5 below `n`, or 0 if `n` is negative.

### Approach
1. Initialize a variable to store the sum of multiples of 3 or 5.
2. Iterate through numbers from 1 to `n-1`.
3. For each number, check if it's a multiple of 3 or 5.
4. If it is, add it to the sum.
5. Finally, return the sum.
   

## Testing the Function
Feel free to try different input values to test the function depending on which language you use!

🎉 Congratulations! You have successfully implemented a function to find the sum of multiples of 3 or 5 below a given number.

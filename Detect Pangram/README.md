#  Detect Pangram

📝 **Problem Statement**  
A pangram is a sentence that contains every single letter of the alphabet at least once. For example, the sentence "The quick brown fox jumps over the lazy dog" is a pangram, because it uses the letters A-Z at least once (case is irrelevant).

Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.

## Plan

### Understanding the Problem
We need to determine whether a given string is a pangram or not. A pangram contains every single letter of the alphabet at least once.

### Input
A string representing a sentence.

### Output
True if the sentence is a pangram, False otherwise.

### Approach
1. Create an empty set to store encountered letters.
2. Iterate through each character in the string.
3. For each character:
    - Check if it is an alphabet letter
    - If it is, convert it to lowercase and add it to the set.
4. After iterating through all characters, check if the set contains all 26 letters of the alphabet.
5. Return True if it does, indicating that the sentence is a pangram. Otherwise, return False.

## Testing the Function
Feel free to test the function with different pangram and non-pangram sentences to verify its correctness.

🎉 Congratulations! You have successfully implemented a function to determine whether a given string is a pangram or not.

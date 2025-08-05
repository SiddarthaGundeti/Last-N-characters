# Last-N-characters

Write a program that reads a word and a number N and prints the last N characters of the word.

Input: Forgive
4

Output: give

Approach
Read the input word and the number N.
Calculate the starting index for the last N characters.
Get the last N characters from the word.
Print the result.

Step-by-Step Explanation
Step 1: Read the input

Read the input word using the input() function and store it in a variable word.
Read the input number N using the input() function, convert it to an integer using int(), and store it in a variable no_of_characters.

Step 2: Calculate the starting index

Calculate the length of the word using the len() function and store it in a variable word_length.
Calculate the starting index for the last N characters by subtracting no_of_characters from word_length and store it in a variable start_index.
 
Step 3: Get the last N characters

Get the last N characters from the word by slicing the word from start_index to the end and store it in a variable part.

Step 4: Print the result

Print the result, which is the last N characters of the word, stored in the variable part.

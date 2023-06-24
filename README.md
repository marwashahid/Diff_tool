# Diff_tool

A diff tool is a program that compares two files and shows the differences between them. Diff tools are typically used to compare source code files, but they can also be used to compare any two files.

The code first defines a function called `LCS_helper()` that calculates the longest common subsequence (LCS) of two strings. The LCS is the longest string that is a substring of both strings.

The `diff()` function then uses the `LCS_helper()` function to calculate the LCS of the two strings. The `diff()` function also keeps track of the differences between the two strings, such as which characters were deleted and which characters were inserted.

The `take_diff()` function reads the two files and calls the `diff()` function for each pair of lines. The `take_diff()` function also prints the differences between the two files, such as which lines were deleted and which lines were inserted.

Here is a brief description of the steps involved in the Myers diff algorithm:

1. Calculate the LCS of the two strings.
2. Create a matrix that tracks the differences between the two strings.
3. Backtrack through the matrix to find the differences between the two strings.
4. Print the differences between the two strings.

The Myers diff algorithm is a very efficient algorithm for comparing two strings. The algorithm is typically used to compare large files, such as source code files.
Fun fact: Git uses four different diff algorithm but Myer's is the default one.
I hope this helps! Let me know if you have any other questions. 

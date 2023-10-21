# Shift-Numbers
# Move Numbers to the End
This is a simple Python program that takes a string as input and moves all the numbers in the string to the end while keeping the order of non-numeric characters intact.
Given a string `A`, the program performs the following:
- Scans through the string, identifying numeric characters.
- Removes the numeric characters from their original positions.
- Appends the removed numeric characters to the end of the string.
- Returns the modified string.
## Example
- **Input**: "1good23morning456"
- **Output**: "goodmorning123456"
- Explanation: The program scans the string and moves the numbers (1, 2, 3, and 4) to the end of the string while keeping the order of non-numeric characters (letters) intact.

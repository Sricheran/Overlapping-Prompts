# Overlapping Prompts

# Simple Python Code

**Purpose:**

This program takes a list of prompts as input and identifies the
overlapping elements among them. It then constructs a new word by
concatenating the overlapping elements and the non-overlapping portions
of the prompts.

**Input:**

The program takes two inputs from the user:

The size of each prompt (an integer)

The number of prompts to be added (an integer)

The user is then prompted to enter each prompt one at a time. The prompt
must be a string of characters and must be the same length as the
specified size. If the prompt is invalid, an error message will be
displayed, and the user will be prompted to enter it again.

**Output:**

The program displays two outputs:

A list of the overlapping elements

The constructed word

**Example Usage:**

Enter the size of each prompt: 4

Enter No. of prompts to be added: 7

Enter prompt :ABCD

Enter prompt :SNU\_

Enter prompt :U_CH

Enter prompt :CHEN

Enter prompt :ENNA

Enter prompt :NAI.

Enter prompt :IJKL

\[\'ABCD\', \'SNU\_\', \'U_CH\', \'CHEN\', \'ENNA\', \'NAI.\',
\'IJKL\'\]

The Overlapped elements are: \[\'U\_\', \'CH\', \'EN\', \'NA\'\]

Word is: SNU_CHENNAI.

**Explanation of the Code:**

The program first takes the size of each prompt and the number of
prompts to be added as input from the user. It then creates an empty
list to store the prompts.

For each prompt, the program checks if the length of the prompt is equal
to the specified size. If it is, the prompt is added to the list.
Otherwise, an error message is displayed.

The compare() function takes a list of prompts as input. It first
creates two empty lists to store the overlapping elements and the
constructed word.

The function then iterates over the list of prompts, comparing each
prompt to the next prompt. If the two prompts have an overlapping
substring, the overlapping substring is added to the list of overlapping
elements, and the two prompts are added to the list of prompts to be
concatenated.

The function then concatenates the non-overlapping portions of the
prompts to be concatenated and returns the list of overlapping elements
and the constructed word.

The main part of the program calls the compare() function to get the
list of overlapping elements and the constructed word. It then displays
these outputs to the user.

# Using AI Algorithm

**Algorithm:**

**Identity Algorithm:**
a. Create an empty list common_elements to store the common substrings.
b. Iterate through the prompts, comparing each pair of adjacent prompts.
c. For each pair, find the longest common substring (LCS) between the end of the first prompt and the beginning of the second prompt.
d. If the LCS is not empty, add it to the common_elements list.

**Classical Search Algorithm:**
a. Initialize an empty string final_word.
b. Iterate through the common_elements list in order.
c. For each common substring, check if it is already present in the final_word.
d. If it is not present, append the common substring to the final_word.

By combining these two algorithms, the program effectively identifies overlapping elements among the prompts and reconstructs a cohesive word from them.

## BY:
SRICHERAN CH_22011101023

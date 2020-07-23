# Wordblocks
C Program that searches for words within words, including anagrams.

### Notes:
This project was part of the first year engineering project done back around March-April of 2019, uploaded now due to reasons unknown to either of the creators. The program searches for words within words, for example, 'done' is a word that can be made using the letters of 'wonder'. The user is presented the output in a game format so that he can guess the words for maximum points while the program compares the user input with it's generated list of 'all words within a given word'.\
\
Uses backtracking for permutation creation, the algorithm to which was referenced from, 
> https://www.geeksforgeeks.org/write-a-c-program-to-print-all-permutations-of-a-given-string/ 

\
Stores the program outputs in different files and so uses basic file I/O operations for the purpose of storing huge volume of generated permutations list. *The text files are included with some pre-run values so the developer can get an idea about what data goes into which file.*\
\
Uses binary search operation to check the generated permutations against a pre-defined dictionary of meaningful words.

### Contributors:
@github.com/pranjalpokharel7\
@github.com/Sandace11

# Spell Sentence Determination
A sentence is considered a Spell if it meets the following conditions:
1. No word in the sentence has more than 9 letters.
2. If you concatenate the lengths of all the words as digits, the resulting number is a prime
number.
Your task is to determine if a given string is a Spell.
For this task, you must implement the following functions (Note: You are not allowed to use
functions from the string.h library):
● int number_of_words(char str[]): This function takes a string as a parameter
and returns the number of words in the string. Words are separated by spaces only.
● int nth_word_length(char str[], int n): This function returns the length
of the nth word in the string.
● int is_prime(int number): This function takes an integer as a parameter and
returns 1 if the number is a prime, otherwise 0.
● int is_spell(char str[]): This function returns 1 if the string is a Spell,
otherwise 0. You should use the number

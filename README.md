This project is a menu-driven Python program that demonstrates how to work with strings.
It contains five tasks, each implemented as a function, and a main menu that ties them together.

⸻

1. Palindrome Checker (is_palindrome)
	•	Takes input text, removes spaces and punctuation, and converts everything to lowercase.
	•	Compares the cleaned string to its reverse ([::-1]).
	•	Returns True if both are equal, meaning the text is a palindrome (e.g., madam, racecar).

Key Concepts: string cleaning, lowercasing, slicing.

⸻

2. Vowel and Consonant Counter (count_vowels_consonants)
	•	Iterates over each character of the string.
	•	Uses a simple rule:
	•	If the character is alphabetic and belongs to "aeiou", it’s a vowel.
	•	Otherwise, it’s a consonant.
	•	Returns two values: number of vowels and consonants.

Key Concepts: loops, conditions, character checking.

⸻

3. Most Repeated Character (most_repeated_char)
	•	Uses Python’s collections.Counter to count frequency of characters.
	•	Ignores spaces and non-alphanumeric characters.
	•	Returns the character that appears most often along with its count.

Example: "programming" → g appears 2 times.

Key Concepts: frequency counting, dictionaries, Counter class.

⸻

4. Caesar Cipher (caesar_cipher)
	•	A simple encryption technique where letters are shifted by a given number.
	•	If mode is "encrypt", it shifts forward. If "decrypt", it shifts backward.
	•	Preserves case (uppercase vs lowercase).
	•	Leaves numbers, punctuation, and spaces unchanged.

Example:
	•	Encrypt "abc" with shift 3 → "def".
	•	Decrypt "def" with shift 3 → "abc".

Key Concepts: ASCII manipulation (ord, chr), modular arithmetic, encryption basics.

⸻

5. Text Analyzer (Mini Project)
	•	Takes a block of text and performs:
	1.	Word Count → total words.
	2.	Most Frequent Word → word that appears most.
	3.	Longest Word → word with maximum length.
	•	Uses split() to break text into words and Counter to find frequency.

Example Input:
"Python is great and Python is easy"
	•	Word count → 7
	•	Most frequent word → “python”
	•	Longest word → “python”

Key Concepts: text splitting, normalization, Counter, max with key.

⸻

6. Main Program (main)
	•	Provides a menu-driven interface.
	•	Keeps looping until the user selects Exit.
	•	Each menu option calls the corresponding function.
	•	Includes input validation (e.g., checking numbers for shift value in Caesar Cipher).

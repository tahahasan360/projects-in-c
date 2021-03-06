Project Descriptions 

#credit.c
uses the Luhn algorithm to detect fraud and avoid unnecessarily checking against the company database for every potentially fraudulent credit card number. Also detects common credit card numbers and outputs their company name e.g. AMEX = American Express 

#readability.c
calculates the Coleman-Liau index of a text to detect its reading level.

#vigenere.c
takes a polyalphabetic key as a command-line argument and prompts the user to input the plaintext. Encrypts using the Vigenere cipher and outputs the ciphertext. Rejects non-alphabetic keys.

#substitution.c
takes a 26-character polyalphabetic key (rejects if any characters repeated or characters not alphabetic) and prompts the user to input the plaintext. Encrypts using the substitution cipher and outputs the ciphertext.

#tideman.c 
takes the candidates (command-line argument) and the number of voters as its input. Each voter ranks the candidates in their preferred order. Uses graph theory, recursion and the Tideman algorithm to calculate and output the Condorcet winner of the election.

#recover.c
recovers JPEGS (if extractable) from a (partially corrupted) file and outputs them. Takes the name of the corrupted file in the command-line argument and outputs the recovered JPEGS(if any).

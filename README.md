# debitcardlogic
this application gives you the actual logic behind generation of check digit(last digit).
The Luhn algorithm is based around the principle of modulo arithmetic and digital roots.
1. Start from the rightmost digit (i.e. check digit)
2. Multiply every second digit by 2 (i.e. digit at even positions)
3. If the result in step 2 is more than one digit, add them up (E.g. 12: 1+2 = 3)
4. Add the resulting digits to digits at the odd positions
5.The total obtained is some value, should be divisible by 10, only then this number is a valid card number.in such way the last digit is choosen.


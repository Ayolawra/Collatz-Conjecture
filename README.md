# Collatz Conjecture

The Collatz Conjecture is a sequence where a positive integer, n, always reaches one.  It remains conjecture since mathematicians have not been able to prove that the sequence is 1 for every positive integer. 

The sequence starts with the integer, and subsequent terms in the sequence depend on whether the number is even or odd. If the number is even, the next term is half the previous term (n/2 when n mod 2 = 0).  If the number is odd, the next term is 3 times the previous term plus 1 (3n + 1 when n mod 2 = 1).  Eventually, the sequence will reach 1 after a series of steps. 

This project is in Python 3.6 code for the Collatz series, showing each term in the sequence and also includes how many steps it took to reach one.

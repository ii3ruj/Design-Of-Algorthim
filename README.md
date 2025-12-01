# Design-Of-Algorthim

Exercise 1: (Finding greatest common divisor) 
In mathematics, the greatest common divisor (gcd) of two or more integers is the largest positive integer that divides each of the integers. 

For example, the gcd of 8 and 12 is 4. Why?
Divisors of 8 are 1, 2, 4, 8.
Divisors of 12 are 1, 2, 4, 6, 12
Thus, the common divisors of 8 and 12 are 1, 2, 4.
Out of these common divisors, the greatest one is 4. Therefore, the greatest common divisor (gcd) of 8 and 12 is 4.

Write a programming code for a function FindGCD(m,n) that find the greatest common divisor.  You can use any language of Java/C++/Python/Octave.    
	
Find GCD Algorithm : 
Step 1  Make an array to store common divisors of two integers m, n.
Step 2  Check all the integers from 1 to minimun(m,n) whether they divide both m, n. If yes, add it to the array.
Step 3  Return the maximum number in the array.


requirements:

0. you can use any languange you want, your code and test should be runnable
1. commit your baby step in development, you can also add your own test case
2. write a class contains a method, which receive a string number as param, the number is 4 digit number with unique digits. You need to return a string contains "A", "B" or "0000".
A means you guess 1 right number in right position
B means you guess 1 right number but in wrong position
0000 means you guess no right number

eg target is 1234, your guess is 5283, since 2 is right number in right position, 3 is right number in wrong position, so return is "AB"

eg target is 1234, your guess is 3261, since 2 is right number in right position, 3 and 1 are right number but in wrong position, so return is "ABB"

eg target is 1234, your guess is 5678, then return 0000


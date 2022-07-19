# Question 1

You have a book, starting page of the book is 1, which is on the right side when the book is open on page 1.

a spread of the book is a left page and consective right page of the book.

the first spread is 1 alone, but the consective spread have 2 pages.

1st spread = 1, 2nd spread = 2-3, 3rd spread = 4-5 . . . so on.

'S' is consider to be the sum of all the digits of left page number and right page number.

in case of 4-5(3rd spread) .. S = 4+5 = 9.
in case of 14-15(8th spread) .. s = 1+4 + 1+5 = 11

problem:
Given S find the left page number.

eg: 1
input S = 9
- 4+5 = 9
- (4+5) is a valid spread
output = 4
  
eg: 2
input S = 3
- 10 + 11 = 3
- (10+11) is a valid spread
output = 10
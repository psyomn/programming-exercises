

Write a function that takes two arguments: a limit, _lim_, and a list of integers, _x_. The function counts up from 0 by cycling through _x_ and skipping numbers until we find the next number that's a multiple of _x[i]_. For example, when x is the list [5, 7, 3], start counting from 0:

1. Next multiple of 5 is 5
2. Next multiple of 7 is 7
3. Next multiple of 3 is 9
4. Next multiple of 5 is 10
5. Next multiple of 7 is 14
6. Next multiple of 3 is 15

When the count reaches _lim_ or a number above it, return the number of steps it took to reach it. ( `multiple_cycle(15, [5, 7, 3])` would return 6.)

What is the result of `multiple_count(1000000000, [5395, 7168, 2367, 9999, 3])` ?


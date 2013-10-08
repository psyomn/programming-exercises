

While basic arithmetic operations like addition, subtraction, multiplication, etc. seem 'natural' to us, computers think on a very different level: under the hood, computations work with [bitwise operations](http://en.wikipedia.org/wiki/Bitwise_operation), using operators like `~` , `&` , `|` , `^` , and `<<` . Your task is to implement functions for (integer) **addition**, **subtraction**, **negation**, **multiplication**, **division**, **modulo**, and **exponentiation**, without using any "high-level" operators like `+` and `*` . Other statements like "if" and "while", or recursion for functional languages, are fine.

As a hint, you could start with a helper function that increments a binary number, and work from there. Your functions should take signed integer arguments and return signed integer values, rounding down (e.g. `binary_div(14, 4) == 3` , not `3.5` ).

Use your set of functions to implement [this function](http://i.imgur.com/ENkWO.png):

    f(a, b, c, d, e) = (a % e) * (b / (c - a) + exp(d * (-b), e))

What is the result of `f(50, -40, 300, 2, 3)` ?


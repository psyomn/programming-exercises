99 Problems in LISP
===================

These are pretty much copied from [here](http://www.ic.unicamp.br/~meidanis/courses/mc336/2006s2/funcional/L-99_Ninety-Nine_Lisp_Problems.html). 
(Thank you for the nice problems to work on).

*P01* : Find the last box of a list
example 

````lisp
(my-last '(a b c d))
> d
````

*P02* : Find the last but one box of a list

```lisp
(last-but-one '(a b c d))
> (c d)
````

*P03* : Find the K'th element of a list

````lisp
(element-at 2 '(a b c d))
> b
`````

*P04* : Find the number of elements of a list

````lisp
(my-length '(a b c))
> 3
````


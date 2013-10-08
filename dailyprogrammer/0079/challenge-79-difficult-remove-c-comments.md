

In the C programming language, comments are written in two different ways:

- `/* ... */` : block notation, across multiple lines.
- `// ...` : a single-line comment until the end of the line.

Write a program that removes these comments from an input file, replacing them by **a single space character**, but also handles **strings** correctly. Strings are delimited by a `"` character, and `\"` is skipped over. For example:

    int /* comment */ foo() { }
    → int   foo() { }
    
      void/*blahblahblah*/bar() { for(;;) } // line comment
    → void bar() { for(;;) }  
    
      { /*here*/ "but", "/*not here*/ \" /*or here*/" } // strings
    → {   "but", "/*not here*/ \" /*or here*/" }


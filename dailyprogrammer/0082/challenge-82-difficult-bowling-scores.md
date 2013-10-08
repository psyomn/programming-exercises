

Write a program that reads a series of space-separated bowling rolls from input, like this one:

    10 7 3 7 2 9 1 10 10 10 2 3 6 4 7 3 3

Then calculates the scores for each frame according to the [scoring rules for ten-pin bowling](http://en.wikipedia.org/wiki/Ten-pin_bowling#Scoring). An example output for these rolls would be:

    | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10    |
    |-----|-----|-----|-----|-----|-----|-----|-----|-----|-------|
    | X   | 7 / | 7 2 | 9 / | X   | X   | X   | 2 3 | 6 / | 7 / 3 |
    | 20  | 37  | 46  | 66  | 96  | 118 | 133 | 138 | 155 | 168   |
    Total: 168

(You can format your output however you like. If you want, just outputting the scores for each frame (20, 37, 46...) is enough.)

Some other examples to test your program on:

    10 10 10 10 10 10 10 10 10 10 10 10
    
    | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10    |
    |-----|-----|-----|-----|-----|-----|-----|-----|-----|-------|
    | X   | X   | X   | X   | X   | X   | X   | X   | X   | X X X |
    | 30  | 60  | 90  | 120 | 150 | 180 | 210 | 240 | 270 | 300   |
    Total: 300
    
    
    10 9 1 8 1 7 3 5 2 8 1 4 6 8 2 10 9 1 3
    
    | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10    |
    |-----|-----|-----|-----|-----|-----|-----|-----|-----|-------|
    | X   | 9 / | 8 1 | 7 / | 5 2 | 8 1 | 4 / | 8 / | X   | 9 / 3 |
    | 20  | 38  | 47  | 62  | 69  | 78  | 96  | 116 | 136 | 149   |
    Total: 149
    
    
    10 10 10 0 8 10 10 0 0 7 0 6 2 9 0
    
    | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10    |
    |-----|-----|-----|-----|-----|-----|-----|-----|-----|-------|
    | X   | X   | X   | 0 8 | X   | X   | 0 0 | 7 0 | 6 2 | 9 0   |
    | 30  | 50  | 68  | 76  | 96  | 106 | 106 | 113 | 121 | 130   |
    Total: 130


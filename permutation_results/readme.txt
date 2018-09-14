
Given N characters and/or digits, what are possible combinations?
Your ATM PIN number is 4-digit long. What are possible PIN numbers?
According to mathematicians, it is N! (N factorial) numbers.
For example, you use digits: 3, 5, 7, 9. Someone could write a program to "guess" 
24 possible numbers your PIN could be, such as: 3579, 3975, and so on.

Let's look at the problem from array POSITION angle:

A two-position array results in two possibilities:
[0, 1]
[1, 0]

A three-position array results in six possibilities:
[0, 1, 2]
[0, 2, 1]
[1, 0, 2]
[1, 2, 0]
[2, 0, 1]
[2, 1, 0] 

Look at result files for four, five, six, seven, and eight-position produced.
Now you can apply array of [3, 5, 7] or ['a', 'b', 'c'] or ['6', 'x', 'y'] to
the three-position array above to produce combinations for each pattern.
For example:
[357]
[375]
[537]
[573]
[735]
[753]
OR
[abc]
[acb]
[bac]
[bca]
[cab]
[cba] 
OR
[6xy]
[6yx]
[x6y]
[xy6]
[y6x]
[yx6]

A note about the program:
My algorithm may not be the best, but it works!!!
It is the result of my thinking, coding; not copy from that of anyone.

Here is how long it takes to calculate, produce the result for 8 and 9 position patterns.
You can google and verify the result for yourself.

initial pos_list [0, 1, 2, 3, 4, 5, 6, 7] len 8
It takes 18.167758 seconds to calculate result of 40320 permutations

--------------------

initial pos_list [0, 1, 2, 3, 4, 5, 6, 7, 8] len 9
It takes 1657.970676 seconds to calculate result of 362880 permutations





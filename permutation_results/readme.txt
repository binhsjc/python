
PROBLEM STATEMENT:

With THREE distinct digits: [3, 5, 7] OR characters ['a', 'b', 'c'] OR a mixed set of ['6', 'x', 'y']   
What are posible "words" / "permutations" we can produce? With FOUR, FIVE, etc... DISTINCT characters and/or digits 
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


A note about the program:
Here is how long it takes to calculate, produce the result for 8, 9, 10-position patterns.
You can google and verify the result for yourself.

initial pos_list [0, 1, 2, 3, 4, 5, 6, 7] len 8
It takes 0.089944 seconds to calculate result of 40320 permutations
--------------------
initial pos_list [0, 1, 2, 3, 4, 5, 6, 7, 8] len 9
It takes 1.087328 seconds to calculate result of 362880 permutations
--------------------
initial pos_list [0, 1, 2, 3, 4, 5, 6, 7, 8, 9] len 10
It takes 11.076147 seconds to calculate result of 3628800 permutations





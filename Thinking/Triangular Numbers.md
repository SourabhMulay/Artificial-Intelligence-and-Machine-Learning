# Triangular Numbers

Gauss Come up with a formula to get the sum of n natural numbers. Suppose given N = 5. the sum will be: 

`1 + 2 + 3 + 4 + 5 = 15`.

But gauss said let's write them in forward as well as backward direction:

`1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 + 10`

and 

`10 + 9 + 8 + 7 + 6 + 5 + 4 + 3 + 2 + 1`

Now if you add them column wise you'll get (10+1), (9+2), (8+3) and results would be the same i.e `11`. So can i say that If N=10 then I got 11 as an answer exactly N times. So suppose i am getting N+1 which is 11 exactly N times then I can write it as:

As I have added the numbers in both directions so 2 times of SUM must equals to the N * N+1.


`2 * SUM =  11 * 10`

So, 

`SUM = (10 * 11) / 2`

and It shown as: 

`SUM OF (first N Natural Numbers)  = N * (N+1) / 2`


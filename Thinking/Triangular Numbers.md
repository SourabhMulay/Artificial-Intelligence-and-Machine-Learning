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

And They called Triangular Numbers. Becuase you Tried to add them and they form a Triangle...

<img width="1000" height="581" alt="image" src="https://github.com/user-attachments/assets/989d1e60-de86-4d89-994a-42b1711dc217" />

<hr>

### SUM OF N ODD NUMBERS
And what about Numbers with other shapes. Like Square Numbers  `(1, 4, 9, 16 ...)` and these are also `sum of odd Numbers`.

Like:

`1 = 1`

`1 + 3 = 4`

`1 + 3 + 5 = 9`

`1 + 3 + 5 + 7 = 16`

....Continue

and we'll do the same what gauss did...

Lets try:

`1 + 3 + 5 + 7 + 9`

and Backward:

`9 + 7 + 5 + 3 + 1`

and if We add ups the columns! we'll get: (9+1), (7+3), (5+5), (7+3), (9+1) so each time we get 10. 

So, `2 * SUM = 10 * 5`  (Sum of first 5 odd Numbers).

So in term of N what is Nth odd number??  It will be `2 * N - 1`. So in general it can be Written as:

`1 + 3 + 5 + ... 2n-1`

and reversed:

`2n-1 + 2n-3 + 2n-5 .... +1`

So if i add them up...(2n-1+1) (2n+3-3) .....results 2n. 


So here i gets N times 2*N.

So 2 times SUM can be equated to this...

`2 * SUM = N * (2*N)`

`SUM = N*N `


So SUM of first N Odd Numbers is `SQUARE OF N`.


SO we have 1 white coin first then 3 black which are arranged..then 5 white and then 7 black which are arranged in fashion to make a Square.

<img width="1186" height="536" alt="image" src="https://github.com/user-attachments/assets/249729c2-d2e5-4495-857b-9cf40bdffdd8" />



<hr>


We can also show all these in form of SUMMATION. 

<img width="1097" height="652" alt="image" src="https://github.com/user-attachments/assets/c63a80b2-f373-4344-abc1-fd9d7a748537" />


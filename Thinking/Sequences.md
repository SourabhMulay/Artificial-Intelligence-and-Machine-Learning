# Sequences

The Natural Numbers: The list of Numbers like (1,2,3,4,5....) we call them Natural Numbers and We call the infinite list of Numbers as ""Sequence"".

Sequences can be anything, So suppose I write a sequence `1,3,5,7,9,11,13,15,17,19 .....` and predict the next 3 numbers! you might have thought of i am writing the odd numbers. but look the numbers which i have written have all odd digits so if you think the next number is 21. the 21 has "2" as even so it might not what i am expecting. 

So for trangular number we have formula `an = n * (n+1) / 2` and the term ak can be easily derived without knowing or printing whole sequence to get the kth term.

Formulae are one way to do it and sometimes there are precised rule to do it. So take an example:

Rules:

1. First term is 1
2. Each term if obtained from the preceding one by adding 1 to it.

So if you apply these rules together then you'll get all natural numbers. 

Or there might be a Rule:

1. First term is 2
2. Each subsequent term is smallest number which is bigger than all previous terms but it's not multiple of any of them.

`2, 3, 5, 7, 11, 13, 17, 19 .... `

Isn't it the sequence of PRIMES.


## Peano's axioms for the natural numbers

So we know the Natural Numbers ... (1,2,3,4,5 ....)

and Some axioms are given my peano's. So remember a Hilbert Hotel. So Hotel has very special Room called ROOM NO. 1 , each guest comes will be stay in ROOM NO. 1. and Every room n there is next room n+1. So every guest comes those guest moves to room no 1 and every other moved to next room so n+1th room exist. 

So Rule for checking if hotel is full is, check if ROOM NO 1 is occupied. and another is whenever the ROOM NO N is occupied then ROOM No N+1 is Occupied. If these two conditions are statisfied then I can say the hotel is full.

Now if we have Integer Hotel we have rooms goin from ...-ve  0  +ve like (... -2, -1, 0, 1, 2 ...) and this hilbert hotel is not same as the Intger Hotel and the rules which we defined for hilberts  hotel is not applied to the Integer's Hotel. because if all the +ve room no's are occupied then there are negatives left so if n+1th is also occupied then also hotel is not full in case of Integer's Hotel.

We'll use the notations of SET to define the axioms. A set is well defined collection of Objects. So given an object X and Set S. So we can make a decision wether the x is part of Set S or not. So if `x E S` mean x is element of S. and negation will tell us that x is not part of S. 

`C` notation tells us that Something is SUBSET of Something. So If I say `T C S` then i can say that if x is part of T set then x is also part og S. 

Now let's come to **Peano's Axioms for Natural Numbers ( N )** (Rules at hilbert Hotel).

1. `1 E N` ( 1 is part of Natural Numbers Set).
2. For every element `n E N` there is a successor denoted as `n+ E N`.
3. If `m, n E N` and m+ = n+ then m = n.
4. There is no number `n E N` such that the n+ (successor) is 1.
5. Suppose `S C N` (S is subset of Natural Number's Set) such that `1 E S` and if `n E S` then `n+ E S` then `S = N`. (S and N are sets).

So these are rules to check if Hilberts Hotel is FULL.

The 5th axiom is known as `Principle of Mathematical Induction`.  (Proof By induction).

lets take an example ... Theorem:  (SUMMATION from i=1 to N  of i is = ( n * (n+1) ) / 2) 

<img width="1325" height="432" alt="image" src="https://github.com/user-attachments/assets/33cd942f-959a-480a-beef-c7f67a4a4fcf" />

Proof:  So I can say that, P(n) = 1 + 2 + 3 ... n = n * n+1 / 2

So for P(1) = 1 * (1+1) / 2 = 1.

P(1) is also called Base case. and then we can have induction steps.

P(n) is true: 

`1 + 2 + 3 + ... n = (n * (n+1)) / 2`

then ...

`(1 + 2 + 3  ... + n) + (n+1) = n * (n+1) /2 + n+1 = (n^2 + n + 2n + 2) / 2`

which is equals to `(n^2 + 3n + 2) / 2` and if again factorised `(n+1) (n+2) / 2` So we got P(n+1).

`P(n+1) = (n+1) (n+2) / 2`.

So to prove is P(n) is true for each `n E N`. AND S is those n For which P(n) is true. 

Base case tells us that P(1) is true and 1 is element of SET S. and in induction steps we say if P(n) is true then P(n+1) is true. so indirectly it's same saying `n E S` then `n+1 E S`.





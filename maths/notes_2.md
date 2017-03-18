Proofs
=======

## Proof by contradiction

To prove a P is True, we assume P is False (¬P is True) , then use that hypothesis to derive a falsehood or contradictions

if ¬P => F is True , then ¬P has to be False , hence P has to be True.

e.g., 
> √2 is irrational.

> **proof(by contradiction)**: Assume that √2 is rational, since it is rational it can be denoted as p/q form where p and q are coprimes.
> 
> Squaring both sides , 2 = p²/q². =>  2q² = p².
> 
> Above statement means that p is an even  => p² is even
>
> If p is even , then p is divisible by 2 and p² is divisible by 4  => 4|p² => 4|2q² => 2|q2 => q is even 
> 
> If p is even and q is even , then p/q is not the fraction in lowest term => contradiction ∦.



## Proof by induction

#### Induction Axiom

Let P(n) be a predicate . If P(0) is True and ∀ n ∈ N (P(n) => P(n+1)) is True , then ∀ n ∈ N P(n) is True.

If P(0) is True and P(0) => P(1), P(1) => P(2) ... are True, then  P(0), P(1), P(2) ... are True. 

e.g., 

**Theorem:**

> **∀ n ≽ 0 ,  1 + 2 + 3 + ... + n = n(n+1)/2**
>
>_or_
>
> **i = 0 to i = n**
>
> **∑i = n(n+1)/2**
>
> _proof (by induction):_ 
> 
>
> * if n =1 → 1
> * if n <=0 → 0 
>
> The above 2 cases are called edge conditionns.
>
> Let P(n) be the proposition that ∑i = n(n+1)/2
>
> _Base Case:_ 
> P(0) ∑i = 0
>
> _Inductive Step:_
>
> For n ≽ 0 P(n) => p(n+1) is True
>
> Assume P(n) is True for purposes of induction (i.e., assume 1 + 2 + 3 + .. + n = n(n+1)/2).
>
> Need to show 1 + 2 + .. + n + (n+1) = (n+1)(n+2)/2
>
> ⇢ n(n+1)/2 + (n+1)
>
> ⇢ (n² +n +2n +2)/2 = (n+1)(n+2)/2 ✓

**Theorem:**

> **∀ n ∈ N, 3|(n³ - n)**
> 
> _proof (by induction):_
> 
> _Base Case :_ n=0  → 3|0
> 
> _Inductive Step:_
> 
> For n ≽ 0 P(n) => p(n+1) is True
> 
> Examine  (n + 1)³ - (n+1) is divisible by 3
> 
> ⇢ n³ + 3n² + 3n + 1 - n - 1
> 
> ⇢ n³ + 3n² + 2n 
> 
> ⇢ n³ - n + 3n² + 3n
> 
> ⇢  n³ - n is already divisible by 3 and 3n² + 3n is diisible by 3 ✓

Inductions doesn't have to always start from 0. We can start from any value of n ≽ b. 

> Base Case P(b) is True.
> 
> ∀ n ≽ b P(n) => P(n+1)

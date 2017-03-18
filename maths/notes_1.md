


# Proposition
A proposition is a statement that is either True of False.

###### Examples
> * `2 + 3 = 5`

> * `∀ n ∈ N, n² + n + 41 is a prime number`




## Predicate
A Predicate is a propsition whose Truth depends on the value of variable(s)

###### Examples

> * `∀ n ∈ N, n² + n + 41 is a prime number` , this holds True for all numbers till 39, first failure occurs at 40, then it will fail for 41 anyways.

> * `a⁴ + b⁴ + c⁴ = d⁴` has not positive integer solutions:  ∃ a, b, c, d ∈ N+ for which this statement is False.

> * `313(x³ + y³) = z³`  has no positive integer solution: False, and shortest counter example is of thousand digits. (This is an example of elliptical curve).

> * The regions in any map can be covered in Four colors ([color theorem](https://en.wikipedia.org/wiki/Four_color_theorem)) so that adjacent regions have different colors (Two states share the same border, they have different colors): No False evident has came to light so True for now.
(Proof by Pictures are often wrong because our brain locks in the details on how things should look like)

> * Every integer but 2 is the sum of 2 primes ([Goldbach conjecture](https://en.wikipedia.org/wiki/Goldbach%27s_conjecture))

> * [Poincaré conjecture](https://en.wikipedia.org/wiki/Poincaré_conjecture)

> * `∀ n ∈ Z, n>=2 => n²>=4`

## Implication
An implication p => q is True, if p is False or q is True.

| p  | q   | p => q  | 
|----|:---:|--------:|
| T  | T   |    T    |
| T  | F   |    F    |
| F  | T   |    T    |
| F  | F   |    T    |

* If pigs fly => I'm king is True, because Pigs don't fly , so p is False, no matter what q is! 



| p  | q   | p => q  |  q => p |  p <=> q | 
|----|:---:|--------:|--------:|---------:|
| T  | T   |    T    |   T     |   T      |
| T  | F   |    F    |   T     |   F      |
| F  | T   |    T    |   F     |   F      |
| F  | F   |    T    |   T     |   F      |

* `∀ n ∈ Z, n>=2 <=> n²>=4`  <=> means if and only if
This implication is False (e.g, -3). Implication has to be both ways.


## Axioms
An axiom is a preposition that is assumed to be True. There is no proof of that , you just assume it to be True.
> * if a = b & b = c then a = c

Axioms can be contradictory.

###### Eculidian Geometry
> Given a line L and a point P not on L , there is exactly 1 line through P parallel to L.

###### Spherical Geometry
> Given a line L and a point P not on L , there is no line through P parallel to L.

###### Hyperbolic Geometry
> Given a line L and a point P not on L , there can be infinitely many line through P parallel to L.


Axioms should be :

* Consistent
* Complete

**A set of axioms is consistent if no propostion can be both proved True and False.**

**A axiom is said to be complete if it can  be used to prove proposion either True of False.**
# Discrete

https://www.eecs.umich.edu/courses/eecs203/refs.html
https://math.berkeley.edu/~mhaiman/math55-spring21/

1. Using the premises
i. 𝑝 ∨ 𝑞 → ¬𝑟
ii. (𝑝 ∨ 𝑟) ∧ 𝑞
Provide a formal deductive argument with the conclusion “p”. Justify each step.

Because (ii) is true, q must be true. Then, (p v q) is true. Since (p v q) -> ¬𝑟, r must be false. Then, since (p v r) ∧ q is true, (p v r) must be true. Since r is false, p must be true. 


1. q by (ii)
2. p v q by 1
3. ¬𝑟 by 2 and (i)
4. (p v r) by (ii)
5. p by 3 and 4

2. Provide a deductive proof to show that from the premises
(𝑝 ∧ 𝑞) → 𝑟
¬𝑟 → (𝑝 ∧ 𝑞)
𝑝 ∨ 𝑞
𝑟 → ¬𝑞
Provide a formal deductive argument with the conclusion “p”. Justify each step.

3. Prove that (¬𝑝 → ((𝑞 ∨ 𝑟) ∧ (¬𝑞 ∧ ¬𝑟)) → 𝑝 is a tautology using the rules of logic.

3) Consider the recursion X(n)=2X(n-1)+2 with the initial condition that of X(1)=1. Using induction
prove that a closed-form solution to this recurrence is X(n)=2n+2n+1

1) Prove that there exist two powers of 2 that differ by a multiple of 222. That is,
∃𝑥 ∃𝑦 (222|(2𝑦 − 2𝑥)) where x and y are positive integers.

2) Let Sn = {1,2,3,4,....,n} and let an denote the number of non-empty subsets of S that
contain no consecutive integers. Find a recurrence relation for an. Note that a0=0 and
a1=1. [8]

Solve the recurrence relation an = 5an−1 − 6an−2 for n ≥ 2, a0 = 1, a1 = 0

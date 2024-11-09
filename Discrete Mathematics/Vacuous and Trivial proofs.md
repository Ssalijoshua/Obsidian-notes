- We can quickly prove that a conditional statement p → q is true when we know that p is false, because p → q must be true when p is false. If we can show that p is false, then we have a proof called **Vacuous proof.**
#### Example
1) Show that the proposition P(0) is true, where P(n) is “If n > 1, then n^2 > n” and the domain consists of all integers.

==Solution:== Note that P(0) is “If 0 > 1, then 02 > 0.” We can show P(0) using a vacuous proof. Indeed, the hypothesis 0 > 1 is false. This tells us that P(0) is automatically true.

==Remark:== The fact that the conclusion of this conditional statement, 0^2 > 0, is false is irrelevant to the truth value of the conditional statement, because a conditional statement with a false hypothesis is guaranteed to be true.

2) Prove that if n is an integer with 10 ≤ n ≤ 15 which is a perfect square, then n is also a perfect cube.
==Solution==:
Note that there are no perfect squares n with 10 ≤ n ≤ 15, because 32 = 9 and 42 = 16. Hence, the statement that n is an integer with 10 ≤ n ≤ 15 which is a perfect square is false for all integers n. Consequently, the statement to be proved is true for all integers n.



#### External Chat
A **trivial proof** and a **vacuous proof** are both methods used in mathematical logic to demonstrate the truth of statements, but they are applied in different situations:

##### 1. Trivial Proof:
A **trivial proof** is used when the conclusion of an implication \( P \implies Q \) is always true, regardless of whether \( P \) (the premise) is true or false. Since \( Q \) is true, the implication is true by definition of logical implication.

- **Example**: If we want to prove the statement "If \( x = 2 \), then \( x^2 \geq 0 \)," this can be done trivially because \( x^2 \geq 0 \) is always true for any real number \( x \), regardless of whether \( x = 2 \) or not. The truth of the conclusion makes the implication true regardless of the premise.

##### 2. Vacuous Proof:
A **vacuous proof** is used to prove an implication \( P \implies Q \) when the premise \( P \) is always false. By the definition of implication, if the premise is false, the whole statement is considered true regardless of the truth value of \( Q \) (the conclusion).

- **Example**: To prove the statement "If \( x > 5 \) and \( x < 3 \), then \( x^2 = -1 \)," we observe that \( x > 5 \) and \( x < 3 \) can never both be true at the same time (there is no such \( x \) that satisfies both conditions), so the premise is always false. Therefore, the implication is vacuously true.

##### Summary:
- **Trivial proof**: The conclusion \( Q \) is always true, so the implication holds regardless of the premise.
- **Vacuous proof**: The premise \( P \) is always false, so the implication is considered true no matter what the conclusion is.
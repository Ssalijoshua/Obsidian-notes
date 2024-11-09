- A direct proof of a conditional statement p → q is constructed when the ﬁrst step is the assumption that p is true.
- In a direct proof, we assume that p is true and use axioms, deﬁnitions, and previously proven theorems, together with rules of inference, to show that q must also be true.
- Direct proofs lead from the premises to the

#### Examples
- Give a direct proof of the theorem “If n is an odd integer, then n^2 is odd.”
==Solution==: Note that this theorem states ∀nP((n) → Q(n)), where P(n) is “n is an odd integer” and
Q(n) is “n2 is odd.” As we have said, we will follow the usual convention in mathematical proofs
by showing that P(n) implies Q(n), and not explicitly using universal instantiation. To begin a
direct proof of this theorem, we assume that the hypothesis of this conditional statement is true,
namely, we assume that n is odd. By the deﬁnition of an odd integer, it follows that n = 2k + 1,
where k is some integer. We want to show that n2 is also odd. We can square both sides of the
equation n = 2k + 1 to obtain a new equation that expresses n2 . When we do this, we ﬁnd that n2 = (2k + 1)2 = 4k2 + 4k + 1 = 2(2k2 + 2k) + 1. By the deﬁnition of an odd integer, we can conclude that n2 is an odd integer (it is one more than twice an integer). Consequently, we have proved that if n is an odd integer, then n2 is an odd integer.


- Give a direct proof that if m and n are both perfect squares, then nm is also a perfect square. (An integer a is a perfect square if there is an integer b such that a = b2 .)
==Solution==: To produce a direct proof of this theorem, we assume that the hypothesis of this conditional statement is true, namely, we assume that m and n are both perfect squares. By the deﬁnition of a perfect square, it follows that there are integers s and t such that m = s2 and n = t2 . The goal of the proof is to show that mn must also be a perfect square when m and n are; looking ahead we see how we can show this by substituting s2 for m and t2 for n into mn. This tells us that mn = s2 t2 . Hence, mn = s2 t2 = (ss)(tt) = (st)(st) = (st)2 , using commutativity and associativity of multiplication. By the deﬁnition of perfect square, it follows that mn is also a perfect square, because it is the square of st, which is an integer. We have proved that if m and n are both perfect squares, then mn is also a perfect square.
- **Proof by contradiction** is a fundamental proof technique in discrete mathematics and logic. It involves proving that a statement is true by assuming the opposite (the negation of the statement) and showing that this assumption leads to a contradiction — an absurd or impossible situation. This contradiction implies that the original assumption (the negation) must be false, and therefore, the original statement must be true.

### Steps in a Proof by Contradiction

1. **Assume the opposite (negation) of what you want to prove.**
   - If the statement is \(P\), assume \(\neg P\) (not \(P\)).
   
2. **Show that this assumption leads to a contradiction.**
   - Using logical steps, deduce consequences from \(\neg P\). If one of these consequences contradicts a known fact or an established theorem, then the assumption \(\neg P\) is false.

3. **Conclude that the original statement must be true.**
   - Since assuming the negation of \(P\) leads to a contradiction, the original statement \(P\) must be true.

### Formal Representation
If you want to prove that a statement \(P\) is true, you assume \(\neg P\) (not \(P\)). If \(\neg P\) leads to a contradiction, i.e., a falsehood, then \(P\) must be true.

### Example 1: Proving \(\sqrt{2}\) is irrational

**Statement**: \(\sqrt{2}\) is irrational (i.e., it cannot be expressed as a ratio of two integers).

**Proof** (by contradiction):
1. **Assume the opposite**: \(\sqrt{2}\) is rational. This means it can be written as a fraction of two integers \(\frac{a}{b}\), where \(a\) and \(b\) are coprime (i.e., have no common factors other than 1), and \(b \neq 0\).
   
   So, \(\sqrt{2} = \frac{a}{b}\).

2. **Square both sides**: 
   \[
   2 = \frac{a^2}{b^2}
   \]
   \[
   2b^2 = a^2
   \]
   This implies that \(a^2\) is even, since it is equal to \(2b^2\) (an even number).

3. **Conclude that \(a\) must be even**: If \(a^2\) is even, then \(a\) must also be even (since the square of an odd number is odd). So, let \(a = 2k\), where \(k\) is an integer.

4. **Substitute \(a = 2k\) into the equation**:
   \[
   2b^2 = (2k)^2 = 4k^2
   \]
   \[
   b^2 = 2k^2
   \]
   This implies that \(b^2\) is also even, and therefore \(b\) is even.

5. **Contradiction**: We have shown that both \(a\) and \(b\) are even. But this contradicts the assumption that \(a\) and \(b\) are coprime (i.e., they cannot have a common factor other than 1). Since both are divisible by 2, they have a common factor, which is impossible.

6. **Conclusion**: The assumption that \(\sqrt{2}\) is rational leads to a contradiction. Therefore, \(\sqrt{2}\) must be irrational.

### Example 2: No Smallest Positive Rational Number

**Statement**: There is no smallest positive rational number.

**Proof** (by contradiction):
1. **Assume the opposite**: Assume there is a smallest positive rational number, say \(r = \frac{a}{b}\) in its lowest terms (where \(a\) and \(b\) are positive integers with no common factors).
   
2. **Consider \(\frac{r}{2}\)**: The number \(\frac{r}{2} = \frac{a}{2b}\) is also a positive rational number, since \(a\) and \(2b\) are integers, and \(\frac{r}{2} > 0\).

3. **Contradiction**: The number \(\frac{r}{2}\) is smaller than \(r\), which contradicts the assumption that \(r\) is the smallest positive rational number.

4. **Conclusion**: Therefore, there is no smallest positive rational number.

### Example 3: The Sum of a Rational and an Irrational Number is Irrational

**Statement**: If \(r\) is a rational number and \(x\) is an irrational number, then \(r + x\) is irrational.

**Proof** (by contradiction):
1. **Assume the opposite**: Suppose \(r + x\) is rational, meaning \(r + x = q\), where \(q\) is a rational number.

2. **Rewrite the equation**: 
   \[
   x = q - r
   \]
   Since \(q\) and \(r\) are both rational, their difference \(q - r\) is also rational.

3. **Contradiction**: This implies that \(x\) is rational, which contradicts the given assumption that \(x\) is irrational.

4. **Conclusion**: Therefore, the assumption that \(r + x\) is rational must be false, and \(r + x\) is irrational.

### Illustration

Let’s visualize the basic idea using a diagram.

Imagine two paths:

- Path A represents the assumption that your statement \(P\) is true.
- Path B represents assuming the opposite, \(\neg P\) (i.e., \(P\) is false).

When following Path B (the assumption that \(P\) is false), you encounter a roadblock (contradiction). This forces you to conclude that Path B is impossible, and the only valid path is Path A, meaning \(P\) is true.

### Summary of Key Concepts:
- **Proof by contradiction** begins by assuming the opposite of what you want to prove.
- If this assumption leads to an impossibility, the original statement must be true.
- It is a powerful proof technique, often used when direct proof is difficult or unclear.

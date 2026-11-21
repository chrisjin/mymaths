# Cauchy's Theorem: McKay's Alternative Counting Proof

Notes on McKay's cyclic-tuple proof of Cauchy's theorem and its consequences for counting elements and subgroups of prime order.

## From existence to counting

[Read the note](Cauchys_Theorem_GTM148_Final.pdf) · [LaTeX source](Cauchys_Theorem_GTM148_Final.tex)

The note develops McKay's cyclic-tuple counting argument for Cauchy's theorem, as presented in Rotman's *An Introduction to the Theory of Groups*. For a finite group whose order is divisible by a prime $p$, it obtains

$$
N_p=(p-1)(pt+1), \qquad t\geq 0,
$$

where $N_p$ is the number of elements of order $p$. Equivalently, the number of subgroups of order $p$ is congruent to 1 modulo $p$, the prime-order case of the classical subgroup-count theorem of Frobenius.

Two applications are included:

- Every group of order 15 is cyclic.
- A group of order $pq$, with primes $p<q$ and $p\nmid(q-1)$, is cyclic.

## Build the PDF

With a LaTeX distribution providing pdfLaTeX and the packages used in the source, run from the repository root:

```sh
pdflatex -interaction=nonstopmode -halt-on-error Cauchys_Theorem_GTM148_Final.tex
pdflatex -interaction=nonstopmode -halt-on-error Cauchys_Theorem_GTM148_Final.tex
```

The second pass resolves theorem and bibliography references.

## References

- J. H. McKay, “Another Proof of Cauchy's Group Theorem,” *The American Mathematical Monthly* **66**(2) (1959), p. 119. [DOI: 10.2307/2310010](https://doi.org/10.2307/2310010).
- J. J. Rotman, *An Introduction to the Theory of Groups*, 4th ed., Graduate Texts in Mathematics 148, Springer, 1995, p. 74.
- Benjamin Sambale, [*Pseudo Frobenius numbers*](https://benjaminsambale.github.io/pdfs/frobenius.pdf), Theorem 1, for a statement of Frobenius's subgroup-count congruence and further references.

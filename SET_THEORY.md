# Set Theory: Foundational Papers

The evolution of mathematical set theory from Cantor's creative discoveries to modern ZFC foundations.

---

## Naive Set Theory & Transfinite Numbers

### [1874] Georg Cantor: Über eine Darstellung unendlicher linearer Punktmannigfaltigkeiten
"On a Representation of Infinite Linear Point Manifolds" — the **first set theory paper**. Cantor proves the real numbers are uncountable (diagonalization argument precursor). Published in Crelle's Journal.
- https://link.springer.com/article/10.1007/BF01446873
- https://web.maths.unsw.edu.au/~jim/cantor-transcendental.pdf

### [1878] Georg Cantor: Ein Beitrag zur Mannigfaltigkeitslehre
"A Contribution to the Theory of Aggregates" — introduced the concept of one-to-one correspondence (bijection) to define equal cardinality. Distinguished between different "sizes" of infinity.
https://jamesrmeyer.com/infinite/cantor-1878-ein-beitrag

### [1883] Georg Cantor: Grundlagen einer allgemeinen Mannigfaltigkeitslehre
"Foundations of a General Theory of Aggregates" — developed the full transfinite number theory (ordinals and cardinals), including arithmetic of infinite numbers.

### [1895] Georg Cantor: Beitrage zur Begrindung der transfiniten Mengenlehre (Parts I & II)
"Contributions to the Founding of the Theory of Transfinite Numbers" — the definitive presentation of transfinite set theory. Two parts published in *Mathematische Annalen* (Vol. 46 & 47). The last papers Cantor wrote on the subject.
https://archive.org/download/contributionstof00cant/contributionstof00cant.pdf

### [1892] Georg Cantor: Uber eine elementare Lehre von den Transfiniten Grossen
"On an Elementary Doctrine about Transfinite Quantities" (1892) — introduced the diagonal argument to prove ℝ is non-denumerable. Also posed the Continuum Hypothesis (CH) for the first time.
- https://www.history.mcmaster.ca/square/Cantor/cantt15.php
- https://web.maths.unsw.edu.au/~jim/cantor-transfiniten.pdf (English translation)

### [1893] Richard Dedekind: Was sind und was sollen die Zahlen?
"What Are Numbers and What Should They Be?" — provided the first rigorous foundation for the natural numbers and arithmetic *before* ZFC existed. The "Dedekind cut" construction of real numbers.
https://archive.org/download/whatnumbersshouldbe00dedeluoft/whatnumbersshouldbe00dedeluoft.pdf

---

## The Paradoxes

### [1901] Bertrand Russell: On the Ideas of a Class of all Classes / The Logical and Mathematical Development of the Theory of Types
Russell's Paradox: "Does the set of all sets that do not contain themselves contain itself?" Showed that naive set theory (unrestricted comprehension: for any property, there exists a set of all things satisfying it) is inconsistent.
https://www.cambridge.org/core/books/principles-of-mathematics/on-ideas-of-a-class-of-a-class/55A0A350B1007A33E425F02DF85A3D80

### [1902] Bertrand Russell: Letter to Frege (Appendix B of *The Principles of Mathematics*, 1903)
https://archive.org/details/theprincipleofma00russuoft
Russell sent his paradox to Frege, who was in the middle of publishing his *Grundgesetze der Arithmetik*. Frege's horrified addendum is one of the most famous moments in the history of logic.
- https://homepages.uc.edu/~martinj/History_of_Logic/Set_Theory,_The_Infinite,_Logicism/Copi%20-%20Theory%20of%20Logical%20Types.pdf

### [1903] Bertrand Russell: The Principles of Mathematics (Ch. X, XII — Russell's Paradox)
Russell's first attempt to fix naive set theory via the **Theory of Types** — a hierarchy of sets where a set cannot contain itself.
https://archive.org/details/theprincipleofma00russuoft

### [1905] Henri Poincaré: Les mathématiques et la logique (Mathematics and Logic)
Introduced the idea of **"circular definitions"** as the root of paradoxes. Poincaré argued that no definition can refer to a totality to which the defined object belongs.

### [1908] Ernst Zermelo: Zur Theorie der Mengenlehre (On the Theory of Set Theory)
https://link.springer.com/article/10.1007/BF01449992
Zermelo's response to the paradoxes: the first **axiomatic set theory**. Introduced the Axiom of Specification (bounded comprehension) which avoids Russell's paradox by only allowing subsets of already existing sets.

### [1919] Bertrand Russell & Alfred North Whitehead: Principia Mathematica (Vol 1, 1st ed., *10 — Theory of Types)
https://archive.org/details/cu31924001575244
Ramified theory of types with the Axiom of Reducibility — an overly complex solution to Russell's Paradox. Later superseded by ZFC, but for decades the standard foundation.
- (Combined 2nd ed. PDF): https://ia802307.us.archive.org/3/items/principia-mathematica_202307/Principia%20Mathematica.pdf

---

## Zermelo's Axiomatic System (Z)

### [1908] Ernst Zermelo: Untersuchungen uber die Grundlagen der Mengenlehre I
"Investigations on the Foundations of Set Theory I" — the seminal paper that introduced the **first axiomatic set theory** (Z). Seven axioms: Extensionality, Elementary Sets, Separation, Power Set, Union, Axiom of Choice, Axiom of Regularity.
https://plato.stanford.edu/entries/zermelo-set-theory/
- English translation: https://link.springer.com/article/10.1007/BF02448635

### [1909] Felix Hausdorff: Grundzuge der Mengenlehre
"Foundations of Set Theory" — the first comprehensive textbook on set theory. Developed the theory of topological spaces from set-theoretic foundations.
https://archive.org/details/grundzudedemenge00haus

### [1922] Ernst Zermelo: Untersuchungen uber die Grundlagen der Mengenlehre II
"Investigations on the Foundations of Set Theory II" — added the Axiom of Replacement to Z, completing his axiomatization.
https://projecteuclid.org/journals/journal-of-symbolic-logic/volume-11/issue-3/Zermelos-Grundlegung-der-Mengenlehse/jsl/1168489735.pdf

---

## Von Neumann-Bernays-Godel (NBG) & ZFC

### [1925] John von Neumann: Eine Axiomatisierung der Mengenlehre
"An Axiomatization of Set Theory" — introduced the concept of **classes** (distinguishing sets from proper classes) to avoid paradoxes. Also introduced the Axiom of Regularity (Foundation) in modern form.
- https://link.springer.com/article/10.1007/BF01201370
- English translations available in Jean van Heijenoort (ed.), *From Frege to Gödel*

### [1922 / 1923] Abraham A. Fraenkel: Zu den Grundlagen der Cantor-Zermeloschen Mengenlehre
"On the Foundations of Cantor-Zermelo Set Theory" — identified that Zermelo's system could not prove the existence of certain infinite sets (like ω+ω). Introduced the **Axiom Schema of Replacement** (Fraenkel-Skolem replacement), which ZFC needed to be complete.
https://link.springer.com/article/10.1007/BF01446630

### [1923] Thoralf Skolem: Logisch-kombinatorische Untersuchungen uber die Erfullbarkeit oder Bewiesbarkeit mathematischer Satze nebst einem Theorem uber dichte Mengen
"Logico-Combinatorial Investigations on the Satisfiability or Provable-ness of Mathematical Theorems" — independently formulated the Axiom Schema of Replacement. Also proved the **Skolem Paradox** (a countable model can satisfy uncountability axioms).

### [1926] Abraham A. Fraenkel: Einleitung in die Mengenlehre
"Introduction to Set Theory" — the first comprehensive textbook that presented Zermelo-Fraenkel set theory. Became the standard reference for decades.
- https://archive.org/details/einleitungindiem00fraegoog

### [1937] Paul Bernays: A System of Axiomatic Set Theory (Parts I-VI)
https://www.jstor.org/stable/2267836
Bernays' axiomatization, which distinguishes sets from proper classes, forming the core of what later became known as **NBG (Von Neumann-Bernays-Godel) Set Theory**.

### [1940] Kurt Gödel: The Consistency of the Axiom of Choice and the Generalized Continuum Hypothesis
"The Consistency of the Axiom of Choice and of the Generalized Continuum Hypothesis with the Axioms of Set Theory" — published as Annals of Mathematics Studies No. 3. Introduced the **Constructible Universe (L)** and proved that AC and CH are consistent with ZF (they cannot be disproved from ZFC axioms).
https://www.karlin.mff.cuni.cz/~krajicek/scott67.pdf (reprint)

### [1963] Paul Cohen: The Independence of the Continuum Hypothesis
Introduced the method of **forcing** — the most powerful tool in modern set theory. Proved that CH cannot be *proved* from ZFC (completing Gödel's consistency result). Also proved AC is independent of ZF.
- https://arxiv.org/pdf/2102.02901 (formalization — original lecture notes are rare; Scott's reprint above is closest)
- https://math.bu.edu/people/aki/14.pdf

### [1967] J. Donald Monk (ed.): Handbook of Set Theory
https://link.springer.com/book/10.1007/978-1-4020-5754-9
Modern reference covering all standard ZFC extensions and large cardinals.

---

## Axiom of Choice (AC) — The Controversy

### [1904] Ernst Zermelo: Beweis, dass jede Menge wohlgeordnet werden kann
"Proof that Every Set Can Be Well-Ordered" — proved the **Well-Ordering Theorem** is equivalent to the Axiom of Choice. Zermelo's original proof used the Axiom of Choice for the first time.
https://link.springer.com/article/10.1007/BF02418586

### [1905] Henri Lebesgue: Les principes mathématiques dans la science moderne
Lebesgue's public critique of Zermelo's proof, arguing that AC is not constructive and therefore not valid in mathematics. Sparked decades of debate.

### [1924] Stefan Banach & Alfred Tarski: La decomposition d'un ensemble en parties similaires et ses applications a la theorie de l'extension mesuree
"A Decomposition of a Set into Parts Similar to Itself and Its Application to the Theory of Extension and Measure" — the **Banach-Tarski Paradox**: a sphere can be decomposed into 5 pieces and reassembled into two identical spheres. The most striking and controversial consequence of AC.
https://archive.org/stream/collectedpapersof02banacrch/collectedpapersof02banacrch_djvu.txt

### [1973] Paul J. Cohen: Set Theory and the Continuum Hypothesis (2nd ed.)
https://gwern.net/doc/math/1973-jech-theaxiomofchoice.pdf (Jech, The Axiom of Choice — best single reference)
- Also see: https://archive.org/details/isbn_9780121829503 (Jech, Set Theory, 3rd ed. — the definitive modern reference for ZFC)

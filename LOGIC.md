# Logic: Foundational Papers

From the algebraic treatment of logic to the formalization of predicate and relational systems — the papers that defined the syntax and semantics of reasoning.

Propositional logic ⊂ Predicate logic ≈ Relational logic

---

## Propositional Logic

### [1847] George Boole: The Analytical Theory of Logic
The birth of treating logical operations as algebraic variables.
https://archive.org/download/theanalyticaltheo00boolrich/theanalyticaltheo00boolrich.pdf

### [1854] George Boole: An Investigation of the Laws of Thought
Full development of Boolean algebra: AND, OR, NOT as algebraic operations.
https://archive.org/download/investigationlaw00bool/investigationlaw00bool.pdf

### [1910] Bertrand Russell & Alfred North Whitehead: Principia Mathematica (Vol 1, *2 — propositional calculus)
Formalized modern axioms for propositional calculus.
https://archive.org/details/cu31924001575244
- (Combined 2nd ed. PDF): https://ia802307.us.archive.org/3/items/principia-mathematica_202307/Principia%20Mathematica.pdf

### [1928] David Hilbert & Wilhelm Ackermann: Grundzuge der theoretischen Logik (1st ed.)
First textbook to present propositional and predicate calculus as two distinct formal subsystems.
https://archive.org/details/bwb_S0-AWJ-083

### [1930] F.P. Ramsey: On a Problem of Formal Logic
Proved the completeness of propositional logic and the decision problem are solvable for propositional logic (unlike predicate logic — see Church 1933).
https://www.cs.umd.edu/~gasarch/TOPICS/ramsey/ramseyorig.pdf

### [1932] Willard Van Orman Quine: Mathematical Logic (rev. ed., 1981)
https://archive.org/details/mathematicallogic0000quin
Modern pedagogical treatment starting from propositional calculus as a formal system.

### [1936] Alonzo Church: An Unsolvable Problem of Elementary Number Theory
Proved undecidability of first-order logic (which subsumes propositional logic).
https://www.ics.uci.edu/~lopes/teaching/inf212W12/readings/church.pdf

### [1938] Claude E. Shannon: A Symbolic Analysis of Relay and Switching Circuits
Boolean algebra → electrical switching circuits. Birth of digital hardware.
https://www.cs.virginia.edu/~evans/greatworks/shannon38.pdf

### [1938] Alfred Tarski: Der Aussagenkalkul und die Topologie
Propositional logic is structurally identical to Boolean algebras of sets / topology.
https://www.degruyter.com/document/doi/10.4064/fm31-1-103-134/html

---

## Predicate Logic (First-Order Logic)

### [1879] Gottlob Frege: Begriffsschrift (Conceptual Notation)
First formal language with a notation for quantification ("forall", "exists"). Separated syntax from grammar. The foundational leap from propositional to predicate logic.
https://www.informationphilosopher.com/solutions/philosophers/frege/Frege_Begriffsschrift.pdf
- https://archive.org/download/gottlob-frege-begriffsschrift-english/Gottlob%20Frege%20-%20Begriffsschrift%20%28English%29_text.pdf

### [1880] C.S. Peirce: On the Algebra of Logic: A Contribution to the Theory of Notation
Independent development of quantifier notation; early use of existential quantifier.
https://archive.org/download/essaysonappliedp00peirrich/essaysonappliedp00peirrich.pdf

### [1897] Bernard Bolzano: Wissenschaftliche Lehre von der Wahrheit (Vol. 2)
https://archive.org/details/wissenschaftliche02bolauoft
Bolzano introduced the concept of an "interpretation" (Deutung) — a semantic concept of validity that anticipates first-order logic by 80 years. Also developed a form of quantification.

### [1900] David Hilbert: Uber die Grundlagen der Logik und der Arithmetik
https://archive.org/details/ubersiibrdiegri00hilbgoog
Hilbert's address to the International Congress of Mathematicians in Paris, laying out the formalism project.

### [1928] David Hilbert & Wilhelm Ackermann: Grundzuge der theoretischen Logik (1st ed.)
https://archive.org/details/bwb_S0-AWJ-083
First textbook to clearly present the syntax and semantics of first-order logic (quantifiers, variables, substitution rules) and to ask the Entscheidungsproblem.

### [1930] Kurt Gödel: Die Vollstandigkeit der Axiome fur die logische Funktionenvorkalkul (Completeness of First-Order Logic)
https://www.w-k-essler.de/pdfs/goedel.pdf
Proved the completeness of first-order predicate logic: every semantically valid formula is provable from axioms. This is the *other* Gödel theorem.

### [1933] Alonzo Church: An Unsolvable Problem of Elementary Number Theory
Proved the undecidability of first-order predicate logic (Church's Theorem): no general decision procedure exists for determining truth of a logical formula in predicate logic (though it IS decidable for propositional logic — see Ramsey 1930).
https://www.ics.uci.edu/~lopes/teaching/inf212W12/readings/church.pdf

### [1935] Jacques Herbrand: Recherches sur la theorie de la demonstration (Paris PhD thesis)
Chapter 4 develops a method for first-order logic without quantifiers. Chapter 5 introduces "Herbrand's Theorem" — the fundamental tool for automated theorem proving: reducing first-order validity to propositional validity on a set of ground instances (Herbrand universes). Herbrand's work directly connects predicate calculus to computation.
- http://www.numdam.org/item/THESE_1930__110__1_0.pdf
- https://archive.org/details/logicalwritingse0000jacq

### [1936] Alan M. Turing: On Computable Numbers, with an Application to the Entscheidungsproblem
Turing machines provide the computational model; Turing proves the undecidability of first-order logic by reduction from the Halting Problem.
https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf

### [1941] Alfred Tarski: Introduction to Logic and to the Methodology of Deductive Sciences
The standard pedagogical introduction to predicate logic. Clear exposition of variables, quantifiers, and the satisfaction relation.
https://ia802903.us.archive.org/8/items/in.ernet.dli.2015.55148/2015.55148.Introduction-To-Logic-And-To-The-Methodology-Of-Deductive-Science-1941.pdf

### [1944] Alfred Tarski: The Concept of Truth in Formalized Languages
Formal definition of truth for first-order logic. The "T-schema": "Snow is white" is true iff snow is white. Foundation of model theory.
http://www.thatmarcusfamily.org/philosophy/Course_Websites/Readings/Tarski%20-%20The%20Concept%20of%20Truth%20in%20Formalized%20Languages.pdf

### [1983] Wilfrid Hodges: A Shorter Model Theory
https://archive.org/details/shortermodeltheo0000hodi
Modern treatment of first-order logic through model theory.

---

## Relational Logic

### [1870] Augustus De Morgan: The Syllogism, Viewed in Relation to the More General Optical Principle
https://archive.org/download/collectedlogical01degoog
De Morgan established that relations are fundamental to logic. Proved that the traditional Aristotelian syllogism is inadequate and that all valid syllogisms can be derived from relational premises.

### [1879] Charles S. Peirce: Description of a Notation for the Logic of Relatives
https://academic.oup.com/mn/article/doi/10.1093/mn/4.1/10/1045503
First formulation of the algebra of relations. Peirce showed that relations can be treated as objects of algebraic manipulation. Introduced the matrix representation of relations.

### [1880] C.S. Peirce: On the Algebra of Logic: A Contribution to the Theory of Notation
Extended the algebra of relations to include quantification over binary relations.
https://archive.org/download/essaysonappliedp00peirrich/essaysonappliedp00peirrich.pdf

### [1882] C.S. Peirce: On the Algebra of Logic — Supplement
https://archive.org/details/essaysonappliedp00peirrich/essaysonappliedp00peirrich.pdf
Introduced the concept of conjugation and iteration in the algebra of relations.

### [1895] Ernst Schroder: Vorlesungen uber die Algebra der Logik, Dritter Band: Algebra und Logik der Relative
The definitive text on the algebra of relations (1000+ pages in three volumes). Schroder systematized Peirce's work and provided the comprehensive treatment of the calculus of relations as an infinite, non-finitely axiomatizable theory.
https://archive.org/details/vorlesungenuberd00schruoft (Vols 1-2), third volume available in archives

### [1897] Bertrand Russell: On the Idea of Multiplicity in Logic
https://www.cambridge.org/core/books/principles-of-mathematics/on-the-idea-of-multiplicity-in-logic/6B5D6F2B4F8A2C9A0D3B5F2E6A4C3D1E
Russell's early work showing that the logic of relations can serve as the basis for arithmetic.

### [1914] Bertrand Russell: The Principles of Mathematics (Ch. 11, 32)
https://archive.org/details/theprincipleofma00russuoft
Comprehensive treatment of the logic of relations. Russell shows that every relation can be reduced to the three primitive relations: identity, conjunction of terms, and relative product.

### [1928] Alonzo Church: The Concept of a Reducible Function (and Relational Logic)
https://archive.org/details/annalsofmathematic301928/30

### [1949] Alfred Tarski: Der Wahrheitsbegriff und die fundamente der semantik
Foundation of the algebra-geometry connection.
https://archive.org/details/tarskicollectedworks

### [1987] Alfred Tarski & Stephen Givant: A Formalization of Set Theory Without Variables
AMS Colloquium Publications, Vol 41
https://www.ams.org/books/coll/041/coll041-endmatter.pdf
Shows that predicate logic with no free variables but with relational atoms (relations of arbitrary arity as atomic formulas) can serve as a foundation for all of set theory.

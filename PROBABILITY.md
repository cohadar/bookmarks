# Probability: Foundational Papers

The evolution of probability from games of chance to a rigorous branch of mathematics.

---

## The Origins: Games of Chance

### [1654] Blaise Pascal & Pierre de Fermat: Correspondence on the Problem of Points
https://www.williamryderjones.com/uploads/1/0/7/6/10764667/1654.pascal-fermat_correspondence.pdf
The first exchange that created probability theory as a mathematical discipline. Fermat's combinatorial approach and Pascal's recursion on expected value ("points of the dice") defined the field.

### [1657] Christiaan Huygens: "De Ratiociniis in Ludo Aleae" (On Reasoning in Games of Chance)
https://archive.org/details/de-ratiociniis-ludo-aleae-huygens.pdf
The first printed treatise on probability. Introduced "expected value" (spes = mathematical expectation) for the first time, and extended the Problem of Points.

### [1713] Jakob Bernoulli: "Ars Conjectandi" (The Art of Conjecturing)
https://archive.org/download/in.ernet.dli.2015.169740/2015.169740.Ars-Conjectandi_djvu.txt
The birth of *mathematical* probability theory. Bernoulli proved the *Law of Large Numbers* (his "fundamental theorem"), transforming probability from a theory of *chance* (future random events) to a theory of *knowledge* (past unknown events, i.e., statistics).

### [1738] Abraham de Moivre: "The Doctrine of Chances"
https://archive.org/download/doctrineofchance00moiv
Introduced the **Normal Distribution** (Gaussian curve) as an approximation for binomial distributions. Also derived the **de Moivre–Laplace theorem** (a precursor to the Central Limit Theorem).

---

## Classical Theory: Laplace and Symmetry

### [1812] Pierre-Simon Laplace: "Theorie analytique des probabilites" (Analytic Theory of Probability)
https://archive.org/details/10613073
The culmination of *classical probability theory*. Laplace unified Bayes' rule, the normal distribution, least squares, and the law of large numbers into a single framework. Introduced the **Principle of Indifference** ("indifference" or "insufficient reason") — if no information distinguishes between outcomes, assign them equal probability.

### [1908] Paul Leibniz: "Recherches sur la principe de probobilites"
https://www.numdam.org/item/RHM_1993__4__73_0.html
Critique of Laplace's Principle of Indifference: Leibniz proved it is mathematically ambiguous because the *partition* of the sample space is underdetermined. This opened the door for the debate between classical (objective) and subjective probability.

---

## Subjective Probability: Bayesian Foundations

### [1826] Thomas Bayes: "An Essay towards solving a Problem in the Doctrine of Chances"
https://bayes.wustl.edu/Manual/an.essay.pdf
Published posthumously (1763) by Richard Price. First formal statement of **Bayes' Theorem**: updating beliefs based on evidence. The birth of *inverse probability*.

### [1926] F.P. Ramsey: "Truth and Probability"
https://fitelson.org/probability/ramsey.pdf
The birth of **subjective probability** (degree of belief). Ramsey defined probability not as an objective property of the world but as *rational degrees of belief* — measured by an agent's willingness to bet. His "Betting Theorem" proved that rational agents must obey the axioms of probability.

### [1930] Richard von Mises: "Wahrscheinlichkeitsrechnung" (Probability Calculus)
https://archive.org/details/wahrscheinlichke00misesuoft
Proposed the **frequency interpretation** of probability: the probability of an event is the limit of its relative frequency in an infinite ensemble of trials. Formally defined "collectives" (random sequences).

### [1937] Bruno de Finetti: "La prévision: ses lois logiques, ses sources subjectives"
https://www.numdam.org/item/AIHP_1937__7_4_1_1_0.pdf
The definitive paper on **subjective probability**. De Finetti proved the **Representation Theorem** for exchangeable sequences: any agent who assigns subjective probabilities to events and updates them consistently will, in the infinite limit, use the same mathematics as a frequentist. "PROBABILITY DOES NOT EXIST" (de Finetti, 1974) — probabilities are purely mental states.

### [1954] Leonard Savage: "The Foundations of Statistics" (based on 1937–1939 Princeton thesis)
https://archive.org/details/foundationsofsta00savo
Unified **subjective probability and decision theory**. Savage proved (the **Sure Thing Principle** / "Savage's axiom") that any agent who makes consistent decisions under uncertainty *must* be using Bayesian updates. This is the "Dutch Book Theorem" in its most general form.

### [1972] R.T. Cox: "Probability and Logic"
https://philarchive.org/archive/CAXPAA
Proved that *any* system of qualitative logic implies a unique set of quantitative axioms: the axioms of probability theory. In other words, if you want to reason with partial truth values, you *must* use Bayesian probability. This is the strongest argument for probability theory as the *only* possible logical extension of classical boolean logic.

### [1990] E.T. Jaynes: "Probability Theory as Logic"
https://bayes.wustl.edu/etj/prob/book.pdf
Modern extension of Cox's result. Jaynes showed that probability theory, properly interpreted, *is* logic. Deduction is the limit where probabilities are 0 or 1; everything else is inductive logic. The most authoritative modern defense of the view that "probability theory is just logic."

---

## The Mathematical Foundation: Kolmogorov's Axioms

### [1930] Andrei Kolmogorov: "Sulla determinazione deile regioni elemenatri assolute di uno spazio a n dimensioni"
https://link.springer.com/article/10.1007/BF02416869
First attempt to ground probability on measure theory.

### [1933] Andrei Kolmogorov: "Grundbegriffe der wahrscheinlichkeitsrechnung" (Basic Concepts of Probability Theory)
https://archive.org/download/foundationsofthe00kolm/foundationsofthe00kolm.pdf
The **definitive paper** that made probability a branch of measure theory (not just a special application of analysis). Introduced the three axioms (non-negativity, normalization of the sample space, sigma-additivity). The **modern standard**.

### [1939] Stanislav Ulam: "Sur une class de systames dynamiques équivalents aux systèmes ergodiques"
https://www.numdam.org/item/RHL_1939__11_1_66_0.pdf
Connected ergodic theory (Birkhoff, von Neumann) with Kolmogorov's axioms. Showed how probability, dynamics, and measure theory converge.

### [1957] Mark Kac: "On Concepts of Axiomatization of Probability Theory"
https://www.mathunion.org/fileadmin/ICM/Proceedings/ICM_1954.pdf
Post-Kolmogorov foundations review. Showed how Kolmogorov's axioms unified all prior probability traditions (classical, frequentist, subjective) under one formal umbrella.

---

## The Philosophical Challenge: Quantum and Non-Boolean Probability

### [1936] George Birkhoff & John von Neumann: "The Logical Calculus of Quantum Mechanics"
https://www.jstor.org/stable/pdf/1968628.pdf
Proved that quantum experiments **cannot** be represented within standard Kolmogorov probability theory because they violate the distributive property of Boolean algebra. Proposd a new form of probability based on **orthomodular lattices** — non-Boolean probabilities.

### [2010] C. Fuchs, B. Schneiders, et al.: "QBism, the Perimeter of Quantum Bayesianism"
https://arxiv.org/pdf/1003.5257.pdf
Modern revival of applying subjective probability ("Bayesianism") to quantum mechanics. Reinterpreted the quantum wavefunction not as reality, but as an agent's subjective belief about future experiences.

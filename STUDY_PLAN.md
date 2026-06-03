# FOUNDATIONS STUDY PLAN

A roadmap to understanding the evolution of formal systems: from the logicism of Russell and Whitehead to the algorithmic capabilities of modern computing.

## Phase 1: The Grammar (Logic)
The foundation of all formal systems. Before defining structures, we must define the rules of valid reasoning.

1.  **Propositional Logic**
    *   **Focus:** Truth tables, logical connectives (AND, OR, NOT), tautologies.
    *   **Goal:** Understand basic validity without looking inside statements.
2.  **Predicate (First-Order) Logic**
    *   **Focus:** Quantifiers (`∀`, `∃`), variables, domains of discourse.
    *   **Goal:** The "language" of mathematics. Being able to say "For all x..."
3.  **Herbrand's Theorem**
    *   **Focus:** Unification and automated theorem proving.
    *   **Paper:** **[1930] Jacques Herbrand: Recherches sur la théorie de la démonstration**
    *   *Reference:* `README.md` or `backups/1930_recherches...`

## Phase 2: The Canvas (Set Theory)
Mathematics needs a "sandbox" to build structures. Logic provides the syntax; Sets provide the objects.

4.  **Naive Set Theory**
    *   **Focus:** Unions, intersections, power sets, Cartesian products.
    *   **Goal:** Comfortable with the concept of "collections of objects."
5.  **ZFC Axioms**
    *   **Focus:** Axiom of Choice, Infinity, Replacement, Separation.
    *   **Goal:** Understand why "Russell's Paradox" happened and how formal axioms solve it.

## Phase 3: The Bridge (Formal Languages)
The transition from abstract structure to mechanical processing.

6.  **Finite Automata & Regular Languages**
    *   **Focus:** States, transitions, Regex.
    *   **Goal:** Understanding the simplest possible computer.
7.  **Context-Free Grammars**
    *   **Focus:** Recursion, syntax trees, parsing.
    *   **Goal:** How compilers decide if code is "valid" (e.g., matching parentheses).

## Phase 4: The Engine (Computability)
We now have the grammar and the sandbox. We define what "processing" actually means.

8.  **Lambda Calculus**
    *   **Focus:** Abstract functions, recursion without variables.
    *   **Goal:** The mathematical basis of functional programming (Lisp, Haskell).
9.  **Turing Machines**
    *   **Focus:** Tapes, heads, state transition tables.
    *   **Goal:** The proof of the Universal Computer.
10. **The Church-Turing Thesis**
    *   **Focus:** Proving that Lambda Calculus, Turing Machines, and Recursive Functions are mathematically identical in power.
    *   **Paper:** **[1936] Alan M. Turing: On Computable Numbers**

## Phase 5: The Limits (Undecidability)
Using the tools from the previous phases to find the "walls" of reality.

11. **Gödel's Incompleteness Theorems**
    *   **Focus:** Gödel numbering (encoding math as numbers), self-reference.
    *   **Paper:** **[1931] Kurt Gödel: Über formal unentscheidbare Sätze...**
12. **The Halting Problem**
    *   **Focus:** Proof by contradiction. Showing that some problems cannot be solved by any algorithm.
    *   **Paper:** **[1936] Alonzo Church: An Unsolvable Problem...**

## Phase 6: The Physical Implementation
Translating math circuits into hardware.

13. **Boolean Algebra & Switching Circuits**
    *   **Focus:** Translating logical propositions into electrical relay circuits.
    *   **Paper:** **[1938] Claude E. Shannon: A Symbolic Analysis of Relay and Switching Circuits**

## Phase 7: The Performance (Complexity)
If a problem is solvable, how much time and memory does it take?

14. **Computational Complexity**
    *   **Focus:** P vs. NP, Time/Space complexity classes.
    *   **Goal:** Understanding the difference between "easy" and "hard" problems.

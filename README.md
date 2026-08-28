# Optimal Stopping: 1-Dimensional Free Boundary Applications

Undergraduate honors thesis, B.S. Mathematics, The University of Texas at Austin (2026).

**Author:** Max David Feldman
**Supervisor:** Dr. Mihai Sîrbu

## About

An expository thesis on the theory of optimal stopping and its solution by free
boundary methods. It develops the general theory first, then works through two
applications from financial mathematics that are also worked examples of the
free boundary technique.

- **Part I — Preliminaries.** Continuous time martingale theory, the essential
  supremum, and the Markov / strong Markov properties (including
  Ornstein-Uhlenbeck processes).
- **Part II — Optimal Stopping.** The general non-Markovian problem and its
  solution via the Snell envelope, followed by motivation for the Markovian case.
- **Part III — Perpetual American Put Option.** The Black-Scholes model and a
  characterization of the solution, as a demonstration of Markovian structure.
- **Part IV — An Ornstein-Uhlenbeck Example.** Reduction of the value function to
  one variable, conversion to a free boundary problem, and derivation and
  verification of the candidate solution (following Peskir and Shiryaev).

## Building

The source is a single LaTeX file, `ThesisOutline.tex`, with figures in `media/`.

```sh
latexmk -pdf ThesisOutline.tex
./clean.sh                       # remove .aux, .log, and other build artifacts
```

Build artifacts and PDFs are not tracked in this repository.

## References

The main sources are Karatzas & Shreve (*Brownian Motion and Stochastic
Calculus*; *Methods of Mathematical Finance*), Revuz & Yor, Protter, Shiryaev
(*Optimal Stopping Rules*), and Peskir & Shiryaev (*Optimal Stopping and
Free-Boundary Problems*). Full bibliography is in the thesis.

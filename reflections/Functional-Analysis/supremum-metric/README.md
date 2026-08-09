# From Euclidean Distance to Function Distance

**A Mathematical Exploration of the Supremum Metric**

---

##  Overview

This repository contains a concise mathematical article exploring the transition from the familiar Euclidean notion of distance between points to the notion of distance between functions using the **supremum metric** (also called the **uniform metric**).

The article focuses on:

- Why pointwise distance alone is insufficient for comparing functions.
- How the supremum aggregates infinitely many pointwise differences into a single scalar.
- The connection between the supremum metric and **uniform convergence**.
- Examples illustrating domain dependence and the finiteness of the supremum.

---

##  Contents

- `From_Euclidean_to_Function_Distance.pdf` – The compiled article.
- `main.tex` – The LaTeX source.
- `preamble.tex` – The LaTeX preamble used for the article.
- `README.md` – This file.

---

##  Purpose

This article was written as a personal reflection on a fundamental idea in functional analysis:

> **How do we measure the distance between two functions?**

The central insight is:

> **A function-to-function distance must convert infinitely many pointwise differences into one scalar quantity.**

The article is intended to be accessible, intuitive, and mathematically sound. It does not assume prior knowledge of functional analysis, but familiarity with basic real analysis and metric spaces is helpful.

---

##  Key Ideas

| Concept | Description |
|---|---|
| **Euclidean distance** | Distance between two points in Euclidean space, given by the norm of their difference. |
| **Pointwise difference** | For functions \(f\) and \(g\), the difference at each point \(x\) is \(\lvert f(x)-g(x)\rvert\). |
| **Supremum metric** | \(d_\infty(f,g)=\sup_{x\in\Omega}\lvert f(x)-g(x)\rvert\), measuring the largest pointwise discrepancy. |
| **Uniform convergence** | A sequence \(f_n\) converges uniformly to \(f\) precisely when \(d_\infty(f_n,f)\to0\). |
| **Finiteness** | The supremum metric is finite precisely when the difference \(f-g\) is bounded. Compactness of the domain together with continuity is one standard way to guarantee this. |

---

##  Who Is This For?

- Students learning functional analysis or real analysis.
- Self-learners exploring metric spaces and function spaces.
- Anyone interested in how mathematics generalises the notion of distance from points to functions.

---

##  Compilation

To compile the LaTeX source:

```bash
pdflatex From_Euclidean_to_Function_Distance.tex

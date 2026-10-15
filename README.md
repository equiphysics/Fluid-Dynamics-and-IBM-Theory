# Fluid Dynamics and IBM Theory

Lecture slides on fluid dynamics, the immersed boundary method (IBM), solid mechanics for the immersed boundary finite element method (IBFE), and turbulence, by **Laura A. Miller** (Department of Mathematics, University of Arizona).

These are the theory companion to **[Using IB Software](https://github.com/fairyflies9/Using-IB-Software)**, which covers the implementation side: IB2d, IBAMR (including IBFE), VisIt, and Planktos.

Each deck is a LaTeX Beamer source file with a compiled PDF next to it. Click a PDF link to read the slides in your browser.

## Modules

**Module 0: Introduction to fluid mechanics**
- [0-1 Deriving the Navier–Stokes equations](0-Intro-to-Fluid-Mechanics/0-1-Deriving-NavierStokes.pdf)
- [0-2 Nondimensionalization and similarity](0-Intro-to-Fluid-Mechanics/0-2-Nondimensionalization.pdf)

**Module 1: The immersed boundary method**
- [1-1 Introduction to the immersed boundary method](1-Immersed-Boundary-Method/1-1-IBM-Intro.pdf)
- [1-2 Mathematical formulation](1-Immersed-Boundary-Method/1-2-IBM-Mathematical%20Formulation.pdf)
- [1-3 Integral transforms and regularized delta functions](1-Immersed-Boundary-Method/1-3-Integral-Transform.pdf)
- [1-4 Discretization](1-Immersed-Boundary-Method/1-4-IBM-Discretization.pdf)

**Module 2: Solid mechanics** (under construction; LaTeX source only)
- [2-1 Introduction to solids](2-Solid-Mechanics-Under-Construction/2-1-Intro-to-Solids.tex)
- [2-2 Introduction to tensors](2-Solid-Mechanics-Under-Construction/2-2-Intro-to-Tensors.tex)
- [2-3 Displacement and velocity](2-Solid-Mechanics-Under-Construction/2-3-Displacement-Velocity.tex)

**Module 3: The finite element method** (under construction; LaTeX source only)
- [3 Finite element method](3-Finite-Element-Method-Under-Construction/3-Finite-Element-Method.tex)

**Module 4: The immersed boundary finite element method (IBFE)**
- [4-1 Why combine immersed boundary and finite element methods?](4-IBFE/4-1-IBFE-Motivation.pdf)
- [4-2 Solid mechanics for IBFE](4-IBFE/4-2-IBFE-Solids-Prep.pdf)
- [4-3 Mathematical formulation of IBFE](4-IBFE/4-3-IBFE-Math-Formulation.pdf)

**Module 5: Turbulence**
- [5-1 Introduction to turbulence, part 1](5-Turbulence/5-1-Intro-Turbulence-Part1.pdf)
- [5-1 Introduction to turbulence, part 2](5-Turbulence/5-1-Intro-Turbulence-Part2.pdf)
- [5-2 Introduction to RANS, part 1](5-Turbulence/5-2-Intro-RANS-Part1.pdf)
- [5-2 Introduction to RANS, part 2](5-Turbulence/5-2-Intro-RANS-Part2.pdf)
- [5-3 Turbulence closure: RANS, LES, and hybrid methods](5-Turbulence/5-3-Turbulence-Closure-RANS-LES.pdf)
- [5-4 Pipe flow and the transition to turbulence](5-Turbulence/5-4-Transition-Turbulence-Pipes.pdf)

**Sample oral exam questions** (LaTeX source): [Sample Oral Exam Questions/](Sample%20Oral%20Exam%20Questions/)

## Building the slides

The decks compile with a standard TeX Live installation (tested with TeX Live 2024) from either the repository root or the deck's own folder, for example:

```bash
latexmk -pdf "4-IBFE/4-1-IBFE-Motivation.tex"
```

All decks share the style file `ib-tutorials.sty` at the repository root.

## Sources and credits

Each deck ends with a references slide, and every borrowed figure is credited on the slide where it appears. Contributions from students and colleagues are acknowledged in the decks.

Claude (Anthropic) was used to assist with formatting, organization, and clarification of the instructor's original notes.

## License

The slides, text and figures are under the [Creative Commons Attribution 4.0 International license (CC BY 4.0)](LICENSE): you may share and adapt them for any purpose, as long as you give credit. Figures from other sources keep their own terms and are credited on the slide where they appear. The papers listed in `papers/README.md` are under their publishers' licenses.

To credit these notes, cite: L. A. Miller, *Fluid Dynamics and IBM Theory*, https://github.com/fairyflies9/Fluid-Dynamics-and-IBM-Theory.

## Feedback

Please let me know if you find any issues or have suggestions for extensions. You can open an issue on this repository.

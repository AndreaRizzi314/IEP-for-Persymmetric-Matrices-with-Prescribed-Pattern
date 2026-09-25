# Inverse Eigenvalue Problem for Persymmetric Matrices with Prescribed Pattern

Working materials for a final-year project on persymmetric matrices, sign patterns, and inverse eigenvalue questions.

## Current work

- [`report/persymmetric_matrices_draft.tex`](report/persymmetric_matrices_draft.tex): short original LaTeX draft on the definition, basic structure, three sketched `2 x 2` pattern families, the role of `bc`, and the `3 x 3` nilpotent case. It includes worked examples and references.
- [`notebooks/persymmetric_3x3.nb`](notebooks/persymmetric_3x3.nb): Mathematica notebook deriving the characteristic polynomial of a general persymmetric `3 x 3` matrix and testing examples with characteristic polynomial `x^3`.

## Using the files

Compile the LaTeX draft with **pdfLaTeX** (for example, upload the `.tex` file to Overleaf and select pdfLaTeX). A local TeX compiler was unavailable when the draft was created, so a compiled PDF is not included yet.

Open the `.nb` file in Wolfram/Mathematica and evaluate its input cells from top to bottom. Mathematica defines `CharacteristicPolynomial[A, x]` as `det(A - x I)`; the notebook uses the monic convention `det(x I - A)`. In a fresh kernel session, all 15 input cells executed and the final verification cell returned `True`.

The draft distinguishes this project's signed-pattern problem from the **nonnegative** persymmetric inverse eigenvalue problem discussed by A. I. Julio and R. L. Soto, *Linear Algebra and its Applications* **469** (2015), 130–152, [doi:10.1016/j.laa.2014.11.025](https://doi.org/10.1016/j.laa.2014.11.025).

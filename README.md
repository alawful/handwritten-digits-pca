# Handwritten digits with PCA

This linear-algebra project explores how principal component analysis changes the representation of handwritten digits. The notebook reduces the pixel data to a smaller set of components and visualizes how clearly different digit classes separate.

## Contents

- `notebook/handwritten_digits_pca.ipynb` contains the analysis and visualizations.
- `data/digits.csv` is the dataset used by the notebook.

The notebook includes both two- and three-dimensional views. The purpose is exploratory: PCA is used to inspect structure in the data, not to claim a state-of-the-art digit classifier.

## Running

The main dependencies are pandas, NumPy, scikit-learn, Matplotlib, and Plotly. Open the notebook from the repository root so its relative path to `data/digits.csv` can be adjusted or resolved as needed.

## Scope

This was a course project completed with classmates. The repository preserves the completed analysis, while the README describes the result modestly as a PCA study rather than a full recognition system.

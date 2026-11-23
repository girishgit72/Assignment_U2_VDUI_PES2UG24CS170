# Unit 2 VDUI — Solved Assignment

This package contains all six completed activity notebooks (PPT 1, 2, 4, 5, 6, and 7), with executed outputs saved below code cells, plus the supplied CSV datasets.

## How to open
1. Extract this ZIP.
2. Open the folder in Jupyter Notebook or JupyterLab.
3. Open any `*_activity.ipynb` notebook. Outputs are already saved in the notebook.
4. To rerun cells, run the notebook from top to bottom.

## Python packages
The notebooks use common packages including numpy, pandas, matplotlib, seaborn, plotly, scikit-learn, networkx, shap, ipywidgets, and (for the full PPT 4 comparison) `umap-learn`.

If `umap-learn` is unavailable, PPT 4 still runs PCA and t-SNE and prints a clear note that the UMAP panel requires installing `umap-learn`.

## Notes
- PPT 5's Random Forest uses 100 trees in the executed notebook to keep SHAP computation practical in constrained environments; the model, local SHAP explanation, bootstrap confidence intervals, and dashboard are all executed.
- Interactive widgets will be interactive when run in a Jupyter environment with `ipywidgets` installed.

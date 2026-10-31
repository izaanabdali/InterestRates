# UK interest rates and housing

Explores UK house-price growth, bank rates, earnings and inflation using monthly data, lagged features and linear regression.

## Files

Start with `LinearRegression.ipynb`. Existing notebooks retain the original project work.

## Running the work

Use Python with pandas, NumPy, scikit-learn, Matplotlib, Jupyter and openpyxl for the data notebooks; some also use seaborn or odfpy. Open notebooks from their repository root so relative data paths resolve. Check all required input files before execution. Dependencies are not yet version-pinned; results may vary across environments. For the Manim presentation, use its original rendering workflow instead.

## Results and limitations

The saved test R-squared is negative. This is exploratory association analysis, not a reliable forecast or causal estimate. Lag selection currently reuses the test period; use training-only validation before reporting a final test result. Some illustrative plots use manually entered values.

## Contributions

For group coursework, the repository contains team work. Individual responsibilities are not documented here; do not infer sole authorship.

# SynQubi

Quantum-inspired portfolio optimization experiments using QAOA and QUBO
formulations, implemented in Jupyter notebooks.

## Notebooks

- `synqubi_portfolio_optimization.ipynb`  
  End-to-end workflow: data download, QUBO/Ising setup, QAOA sampling,
  brute-force comparison, and visualization.

- `synqubi_qubo_tests.ipynb`  
  Additional experiments and validation for QUBO construction and metrics.

## Quick Start

1. Open `synqubi_portfolio_optimization.ipynb`.
2. Run the install cell to pull required packages.
3. Run the notebook cells in order to generate results and plots.

Notes:
- The notebook downloads market data via `yfinance`.
- Plotly PNG export uses `kaleido`.

## Output

The notebook saves plots to:
`/Users/chevinjeon/Library/Mobile Documents/com~apple~CloudDocs/Documents/QAOA/`

If you want a different output folder, update the `output_path` in the Plotly
cell.

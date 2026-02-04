# SynQubi

SYNQUBI is a modular, risk-aware portfolio optimization framework that treats
optimization as a constrained proposal mechanism inside an agentic pipeline.
The project implements a reproducible QUBO/QAOA case study and benchmarks
QAOA sampling against exhaustive brute-force search on a small asset universe.

Paper title: **SYNQUBI: A Quantum-Optimized Multi Agent for Risk-Aware Financial
Decision-Making**

## Repository Structure

- `synqubi_portfolio_optimization.ipynb`  
  End-to-end workflow: data download, QUBO/Ising setup, QAOA sampling,
  brute-force comparison, and visualizations.

- `synqubi_qubo_tests.ipynb`  
  Additional experiments and validation for QUBO construction and metrics.

## Quick Start

1. Open `synqubi_portfolio_optimization.ipynb`.
2. Run the install cell to pull required packages.
3. Run the notebook cells in order.

Notes:
- Market data is downloaded via `yfinance`.
- Plotly PNG export uses `kaleido`.
- The QAOA sampling cell is the slowest step.

## Outputs

Plots are saved to:
`/Users/chevinjeon/Library/Mobile Documents/com~apple~CloudDocs/Documents/QAOA/`

To change the location, update `output_path` in the Plotly cell.

## Reproducibility Tips

- QAOA outputs vary slightly due to stochastic sampling and optimizer state.
- For faster restarts, cache outputs after sampling and reload them in plot-only
  cells.

## Citation

If you use this work, please cite the SynQubi paper or link to the repo:
`https://github.com/Chevinjeon/SynQubi`.

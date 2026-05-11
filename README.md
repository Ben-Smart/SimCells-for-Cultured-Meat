# SimCells for Cultured Meat

This repository contains Jupyter notebooks used to simulate metabolic behavior for cultured meat workflows.

## Contents

- `SimCell_sim.ipynb`: synthetic cell simulation with ODE-based dynamics.
- `Arg_pathway_sim.ipynb`: arginine-pathway simulation with parameter sweeps and sensitivity analysis.
- `Combined_sim.ipynb`: combined simulation workflow linking pathway kinetics and metabolic model components.

## Usage

1. Create and activate a Python environment.
2. Install required scientific Python packages (`numpy`, `pandas`, `scipy`, `matplotlib`; plus model-specific dependencies such as `cobra` where needed).
3. Open the notebooks in Jupyter/Cursor and select the intended kernel.

## Notes

- Some notebook sections may reference local helper files or datasets not included here.
- Run cells from top to bottom to ensure parameters and functions are initialized correctly.

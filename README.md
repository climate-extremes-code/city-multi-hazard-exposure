# city-multi-hazard-exposure
# Urban multi-hazard analysis (code & results)

Short, reproducible workflows for the paper’s analyses. Notebooks produce the figures and CSV results used in the manuscript.

## Notebooks
1. [notebooks/01_percentile_climate.ipynb](notebooks/01_percentile_climate.ipynb) — percentile-based climate file creation  
2. [notebooks/02_heatwaves.ipynb](notebooks/02_heatwaves.ipynb) — heatwave assessment  
3. [notebooks/03_drought.ipynb](notebooks/03_drought.ipynb) — drought assessment  
4. [notebooks/04_floods.ipynb](notebooks/04_floods.ipynb) — flooding assessment

## How to run
```bash
# (optional) create a fresh environment
# python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate

pip install -r requirements.txt
jupyter lab   # or: jupyter notebook

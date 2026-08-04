# synthetic-data-generator

This project generates synthetic injection histories for an arbitrary number of injection wells. 
The generated data can be used to test and validate models using this data as the input such as the Capacitance-Resistance Model (CRM) that uses injection rates.

The model uses random walk with mean reversion, by default the speed of reversion is set to 0.15333 and works around the initial value.
The initial value of rate for each well is set around an interval.
The values of each run of the code are the same because of the seeds. The default seed is set to 100.

## Requirements

- Python 3.11+
- JupyterLab or Jupyter Notebook

## Dependencies

```bash
pip install numpy pandas matplotlib
```

## Usage

1. Open `synthetic_data_generator.ipynb` in JupyterLab.
2. Run all cells.
3. The notebook will:
   - Generate synthetic injection histories.
   - Plot the injection rates.

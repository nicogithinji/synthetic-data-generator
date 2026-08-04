# synthetic-data-generator

This project generates synthetic injection histories for an arbitrary number of injection wells. 
The generated data can be used to test and validate models using this data as the input such as the Capacitance-Resistance Model (CRM) that uses injection rates.

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

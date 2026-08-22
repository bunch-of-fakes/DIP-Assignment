# Digital Image Processing

Coursework project containing one Jupyter notebook per assignment.

## Structure

- `notebooks/`: assignment notebooks, named `<chapter>.<assignment>_<Description>.ipynb`
- `data/input/`: source images and other input data
- `data/output/`: generated results (ignored by Git)
- `src/`: reusable Python code
- `assets/`: supporting project assets

## Environment

Create or recreate the environment with:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m ipykernel install --user --name dip --display-name "Digital Image Processing"
```

In VS Code, open this folder and select the `Digital Image Processing` kernel for a notebook.

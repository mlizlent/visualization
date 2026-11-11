# visualizations

Python visualization exercises (ex00–ex07).

## Structure

```
ex00/
├── requirements.txt
└── Notebook_ex00.ipynb
ex01/
└── Notebook_ex01.ipynb
...
ex07/
└── Notebook_ex07.ipynb
```

## Environment (ex00)

Create the virtual environment and install the required libraries:

```bash
python3 -m venv ex00/ex00
source ex00/ex00/bin/activate
pip install --upgrade pip
pip install -r ex00/requirements.txt
```

`requirements.txt`:
```
pandas
numpy
jupyter
matplotlib
plotly
```

A Jupyter kernel named `ex00` is registered so all notebooks (`Notebook_ex00.ipynb` … `Notebook_ex07.ipynb`) run on this kernel:

```bash
ex00/ex00/bin/python -m ipykernel install --user --name=ex00 --display-name "ex00"
```

## Libraries

- pandas
- numpy
- jupyter
- matplotlib
- plotly

Python >= 3.9 is used (Python 3.12.3 in this environment).

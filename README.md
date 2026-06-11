# Introduction to Python Practicals

This repository contains the practical notebooks for the **Introduction to Python** course.

## Contents

- Practical 1: Python basics
- Practical 2: Data structures, loops, and control flow
- Practical 3: Functions, files, and working with modules
- Practical 4: Data analysis with NumPy, Pandas, Matplotlib, and Seaborn

## Repository structure

```text
intro-python-practicals/
│
├── README.md
├── requirements.txt
├── environment.yml
├── .gitignore
│
├── practicals/
│   ├── practical_1.ipynb
│   ├── practical_2.ipynb
│   ├── practical_3.ipynb
│   └── practical_4.ipynb
│
├── solutions/
│   ├── practical_1_solutions.ipynb
│   ├── practical_2_solutions.ipynb
│   ├── practical_3_solutions.ipynb
│   └── practical_4_solutions.ipynb
│
├── data/
└── images/
```

## How to download the practicals

Clone the repository:

```bash
git clone https://github.com/alireza-hosseinzadeh/intro-python-practicals.git
cd intro-python-practicals
```

## Option 1: Create the environment with Conda

```bash
conda env create -f environment.yml
conda activate intro-python
```

Then open Jupyter Lab:

```bash
jupyter lab
```

## Option 2: Install packages with pip

```bash
pip install -r requirements.txt
```

Then open Jupyter Lab:

```bash
jupyter lab
```

## Required packages

The practicals use:

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Lab / Jupyter Notebook

## Notes for students

Use the notebooks inside the `practicals/` folder during the practical sessions.

The `solutions/` folder contains completed versions of the exercises. These may be released after the practical sessions, depending on the instructor's preference.

## Notes for instructors

If you use external datasets, place them inside the `data/` folder.

If your notebooks use images or diagrams, place them inside the `images/` folder and refer to them using relative paths.

Example:

```python
import pandas as pd

df = pd.read_csv("../data/example_dataset.csv")
```

## Updating the repository

After editing files locally, run:

```bash
git add .
git commit -m "Update practical materials"
git push
```

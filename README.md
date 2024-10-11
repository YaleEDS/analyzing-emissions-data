# Analyzing Emissions Data

This is a notebook showcasing how to analyze emission data. This is just an example

```
.
├── LICENSE          <-- license for the repo
├── README.md        <-- top-level documentation
├── data
│   ├── processed    <-- processed data directory
│   └── raw          <-- raw data directory
├── environment.yml  <-- conda environment file (for reproucibility)
└── notebooks        <-- python notebooks
```

# How to run these notebooks

Here I will be using `conda` to create my environment. If you do not have conda installed, I suggest using [miniconda](https://docs.anaconda.com/miniconda/) for less bloat

1. Use the `environment.yml` to create a conda environment

```bash
conda env create --file environment.yml
```

2. Activate the environment

```bash
conda activate eds
```

3. Make the `eds` environment accessible from jupyterlab by running the following command

```bash
python -m ipykernel install --user --name eds --display-name eds
```

4. Open the repo in jupyterlab

```bash
jupyter lab --notebook-dir=.
```

5. Now you can (hopefully) open and run the notebooks
# Software and computing environment

On this page you'll find information about the computing environment and datasets that will be used in both of the tutorials in this book.

## *Running tutorial materials locally*

There are two options for creating a software environment: [pixi](https://pixi.sh/latest/) or [mamba](https://mamba.readthedocs.io/en/latest/) / [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html). We recommend using pixi to create a consistent environment on different operating systems. If you have pixi installed, follow the steps below, otherwise, follow the steps for conda/mamba below.

### To use pixi:
1. Clone the book's GitHub repository:   
    ```git clone https://github.com/e-marshall/cloud-open-source-geospatial-datacube-workflows.git```

2. Navigate into the repo environment:
```cd cloud-open-source-geospatial-datacube-workflows```

3. Execute `pixi run` for each tutorial:
```pixi run itslive```
```pixi run sentinel1```

### To use conda/mamba:

1. Clone this book's GitHub repository:  
```git clone https://github.com/e-marshall/cloud-open-source-geospatial-datacube-workflows.git```

2. Navigate into the `book` sub-directory:  
```cd cloud-open-source-geospatial-datacube-workflows/book```

3. Create and activate a conda environment from the `environment.yml` file located in the repo:  
```conda env create -f .binder/environment.yaml```

4. Start Jupyterlab and navigate to the directories containing the jupyter notebooks (`itslive_nbs` and `s1_nbs`):  
```jupyterlab```

Both tutorials also uses functions that are stored in scripts associated with each dataset. You can find these scripts here: [`itslive_tools.py`](../itslive_nbs/itslive_tools.py) and [`s1_tools.py`](../s1_nbs/s1_tools.py).


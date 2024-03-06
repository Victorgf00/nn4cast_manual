# NN4CAST_manual
 Repository containing the nn4cast library and some necessary tools to work with it. It is designed to work with .nc data with coordinates: time, latitude and longitude.

## Installation
**WARNING**: The environment must be compatible with all the dependencies, and it has been tested with python 3.9.16, future versions could be compatible with newer versions of python and other packages You also need to have installed **Anaconda** and **Git**.

**NOTE**: Cartopy has to be installed with conda because pip version does not work

To get the latest version:
```console
    $ conda create -n <your-env-name> python=3.9.16
    $ conda activate <your-env-name>
    (<your-env-name>) $ conda install cartopy
    (<your-env-name>) $ pip install git+https://github.com/Victorgf00/nn4cast
    (<your-env-name>) $ conda install pydot graphviz
```

## Usage
For example usage, look at file    in this repository.


## How to cite this material

DOI: https://doi.org/10.5281/zenodo.10730811

BibTex:
```markdown
@software{galvan_fraile_2024_10730811,
  author       = {Galván-Fraile, Víctor and
                  Martín-del-Rey, Marta and
                  Rodríguez-Fonseca, Belén and
                  Polo-Sánchez, Irene},
  title        = {NN4CAST\_manual},
  month        = mar,
  year         = 2024,
  publisher    = {Zenodo},
  version      = {1.0.13},
  doi          = {10.5281/zenodo.10730811},
  url          = {https://doi.org/10.5281/zenodo.10730811}
}
```

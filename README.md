# NN4CAST_manual
 Repository containing the nn4cast library and some necessary tools to work with it. It is designed to work with .nc data with coordinates: time, latitude and longitude

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

To update to the latest version:
```console
    (<your-env-name>) $ pip install --upgrade git+https://github.com/Victorgf00/nn4cast

# Cookiecutter Crop2ML

_A logical, reasonably standardized, but flexible project structure for sharing crop models components between crops modelling platform._


#### [Project homepage](https://github.com/AgriculturalModelExchangeInitiative/Crop2ML/)


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/AgriculturalModelExchangeInitiative/cookiecutter-crop2ml


[![asciicast](https://github.com/AgriculturalModelExchangeInitiative/Crop2ML/blob/master/doc/images/cookiecutter.png)](https://github.com/AgriculturalModelExchangeInitiative/Crop2ML/blob/master/doc/images/cookiecutter.png)


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```

    ├── LICENSE.txt        <- License file
    ├── README.md          <- The top-level README for AMEI members using this project.
    ├── data/              <- data used for model simulation
    │
    ├── doc/               <- Package documentation
    │
    ├── test/             <- model tests for each language and platform
    │
    ├── crop2ml/          <- model units and composite in crop2ml format.
    │      ├── xml files
    │      ├── Algo/
    |
    │
    ├── src/                <- Executable source in different language and platform
    │   ├── pyx/
    │   ├── java/
    │   ├── py/
        ├── R/
        ├── cpp/
        ├── cs/
        ├── f90/
        ├── Bioma/
        ├── Simplace/
        ├── OpenAlea/
        ├── Record/
   
```

## Contributing

We welcome contributions! [See the docs for guidelines](https://cropml.readthedocs.io/en/latest/).



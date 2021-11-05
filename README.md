# pm21-ox

## Introduction

This is the course material for PM-21, Winter Semester 2021-2022
(year of the Ox), Faculty of Biology, University of Freiburg. The lectures will
be taught by Prof. Dr. Andrew Straw and the tutorials by Yonatan Cohen.

## Run interactively at https://strawlab-rp2.zoologie.uni-freiburg.de

We strongly recommend that you install Anaconda Python on your own computer -
this gives you the tools to run your own code after the class is over on your
own PC. We will help you install Anaconda python and the packages we use in the
course. While we are doing that, for the first few days (or for the entire
course), you may use our server. This will be taken offline shortly after the
course is done.

Login details to https://strawlab-rp2.zoologie.uni-freiburg.de will be discussed
in class.

## Installation with Anaconda

Download the Anaconda Individual Edition from
[here](https://www.anaconda.com/products/individual).

We will demonstrate how to setup an Anaconda environment in class. Use our
[`environment.yml`](https://raw.githubusercontent.com/strawlab/pm21-ox/main/environment.yml)
file to setup your `pm21-ox` environment in Anaconda. **Failure to use the
`environment.yml` file for the class may result in incompatibility with the
exercises in the course.**

## Links

### Ilias

https://ilias.uni-freiburg.de/goto.php?target=crs_2380796&client_id=unifreiburg

Upload your daily assignments as .ipynb files directly into the assignment
folder in Ilias. **Do not change the file name from the original.**

### HisInOne

https://campus.uni-freiburg.de/qisserver/pages/startFlow.xhtml?_flowId=detailView-flow&unitId=45291&periodId=2451&navigationPosition=hisinoneLehrorganisation,examEventOverviewOwn

## The Python Tutor - extremely highly recommended

http://pythontutor.com/

## Some useful Python data science cheat sheets

- https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf
- http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf

## Run on your computer with anaconda

```
conda env create -f environment.yml
conda activate pm21-ox
# Alternatively, try "source activate pm21-ox"
jupyter notebook
```

## Troubleshooting

### Note for macOS users

Before starting `jupyter notebook` from the command line, you may like to type:

    ulimit -n 4096

This will solve [OSError: [Errno 24] Too many open files](https://github.com/jupyterlab/jupyterlab/issues/6727).

## Code of conduct

Anyone who interacts with this software in any space, including but not limited
to this GitHub repository, must follow our [code of
conduct](code_of_conduct.md).

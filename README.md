# Rivercatch

![Continuous integration build in GitHub Actions](https://github.com/git-gurus/rivercatch/workflows/CI/badge.svg?branch=main)

Rivercatch is a command line tool, written in Python,
to process and visualise river measurement data from csv files.

## Main features
Here are some key features of Rivercatch:

- Provide basic statistical analysis of data.
- Ability to work with csv data.
- Generate plots.

## Prerequisites
RiverCatch requires the following Python packages:

- [NumPy](https://www.numpy.org/) - makes use of NumPy's
statistical functions
- [Pandas](https://pandas.pydata.org/) - makes use of Panda's
dataframes
- [GeoPandas](https://geopandas.org/) - makes use of GeoPanda's
spatial operations
- [Matplotlib](https://matplotlib.org/stable/index.html) - uses
Matplotlib to generate statistical plots

The following optional packages are required to run
RiverCatch's unit tests:

- [pytest](https://docs.pytest.org/en/stable/) - RiverCatch's
unit tests are written using pytest
- [pytest-cov](https://pypi.org/project/pytest-cov/) - Adds test
coverage stats to unit testing

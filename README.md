# DataSci Distributions

## Description

As part of an AWS Machine Learning course, I converted distribution code into a Python package by modularizing the code and creating the required files. Then, I distributed the package on PyPi.

The project demonstrates object oriented programming topics such as encapsulation, magic methods, and inheritance of attributes and methods.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Credits](#credits)
- [Questions](#questions)

## Installation

Consider setting up and activating a virtual environment to install the package without affecting your main Python installation. See [Installing packages using pip and virtual environments](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/).

### Prerequisites

[pip](https://pip.pypa.io/en/latest/)

[python3](https://www.python.org/downloads/)

### Installing the package

```
python3 -m pip install datasci-distributions
```

Also, install [matplotlib](https://matplotlib.org/):

```
pip install matplotlib
```

[Additional information about installing PyPi packages.](https://packaging.python.org/tutorials/installing-packages/)

## Usage

Use the package to calculate Gaussian and Binomial distributions including mean, standard deviation, p (float) - probability of an event occurring, n (int) - number of trials from a dataset.

In addition, the package can be used to:

- plot a histogram of the instance variable data using matplotlib pyplot library,
- calculate the probability density function and plot it,
- add together two Binomial distrubtions with equal p or two Gaussian distributions, and
- output the characteristics of the Gaussian instance.

Start the Python interpreter from the terminal by entering:

```
python
```

Then, use the package by entering the following commands:

```
from datasci_distributions import Gaussian
```

or

```
from datasci_distributions import Binomial
```

Then use commands such as:

```
gaussian_one = Gaussian(25, 2)
```

```
gaussian_one.mean
```

```
gaussian_one + gaussian_one
```

## License

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
[License: MIT](https://opensource.org/licenses/MIT)

## Credits

Starter code provided by AWS Machine Learning Foundations Nanodegree Program.

## Questions

Email merriammassey@gmail.com

GitHub [my GitHub profile](https://github.com/merriammassey)

Network-Analysis-Made-Simple
============================

# Getting Set Up

For this tutorial, you will need the following packages:

1. Python 3
2. `matplotlib`
3. `networkx`
4. `pandas`
5. `hiveplot` - do not do `conda install hiveplot`, but `pip install hiveplot`.
6. `numpy`

## Easiest way: Anaconda Distribution of Python

If you have the Anaconda distribution of **Python 3** installed, then follow this set of instructions.

1. `$ cd /path/to/your/directory`
1. Clone the repository to disk:
    1. `$ git clone https://github.com/ericmjl/Network-Analysis-Made-Simple.git`
1. `$ cd Network-Analysis-Made-Simple`
1. `$ conda env create -f environment.yml`
1. `$ source activate network`

Finally, check your environment by running the following command:

1. `$ python checkenv.py`

If you do not have the Anaconda distribution, I would highly recommend getting it. It provides an isolated Python computing environment that will not interfere with your system Python installation, and comes with a very awesome package manager that makes installation of new packages really simple. 

If you're not using Python 3, then check out @jakevdp's talk at SciPy2015 to find out why!

## Alternative way: `pip install`

For those who do not have the capability of installing the Anaconda Python 3 distribution on their computers, please follow the instructions below.

1. Create a virtual environment for this tutorial, so that the installed packages do not mess with your regular Python environment.
    2. `$ pip install virtualenv`
    3. `$ virtualenv network`
    4. `$ source network/bin/activate`
5. `$ pip install matplotlib networkx pandas hiveplot numpy`

Finaly, check your environment:

1. `$ python checkenv.py`

# Issues?

If you're facing difficulties, please report it as an [issue][1] on this repository.

# Dataset Credits

1. Divvy Data Challenge: https://www.divvybikes.com/datachallenge

[1]: https://github.com/ericmjl/Network-Analysis-Made-Simple/issues
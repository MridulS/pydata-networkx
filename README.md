## Networks, Game of Thrones and US Airports.

The contents of this notebooks are also available as a JupyterBook at http://ericmjl.github.io/Network-Analysis-Made-Simple/ (Section 5).

You can also pick up the official EPUB/MOBI/PDF version of the book (Network Analysis Made Simple) on [LeanPub](http://leanpub.com/nams)! Purchasing a copy helps support the authors, and funds future improvements and updates to the book, which you will continue to receive as we make updates!

NOTE: This repo will be updated before the tutorial so make sure to pull new changes.

#### Set Up

For this tutorial, you will need Python 3 and the following packages:

- `networkx`
- `pandas`
- `matplotlib`
- `numpy`
- `jupyter`

Or you can use Binder (only if you have a stable WiFi connection)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MridulS/pydata-networkx/master)

HTML notebooks
- [introduction-and-game-of-thrones-instructor](https://mriduls.github.io/pydata-networkx/introduction-and-game-of-thrones-instructor.html)
- [US-aiports-instructor](https://mriduls.github.io/pydata-networkx/US-aiports-instructor.html)


### Clone/Download the repo

- `$ cd /path/to/your/directory`
- Clone the repository from GitHub
	 `$ git clone https://github.com/mriduls/pydata-networkx`
- `$ cd pydata-networkx`

**OR**

- Download the required notebooks from `https://github.com/MridulS/pydata-networkx/archive/master.zip`
- unzip the files and change the directory to 
		`$ cd pydata-networkx-master` 

### Install packages 
#### Using pip and virtualenv


- Create a virtual environment for this tutorial, so that the installed packages do not mess with your regular Python environment.
    - `$ (sudo) pip install virtualenv`
    - `$ virtualenv -p python3 networkx`
    - `$ source networkx/bin/activate`
- `$ pip install -r requirements.txt`


#### Using Anaconda
If you have the Anaconda distribution of **Python 3** installed, then run the commands below.

- `$ conda env create -f environment.yml`
- `$ source activate networkx`

### Check your environment:

- `$ python checkenv.py`

### Run the Jupyter Notebook

    $ jupyter notebook

Your browser will open to an index page where you can click on a notebook to run it.

### Links

There is an adpated version of this tutorial in Spanish, thanks to [@iris9112](https://github.com/iris9112/) -> https://github.com/iris9112/pycon2019_iris9112

### Credits

This tutorial is built on and inspired by the previous offerings of this tutorial at PyData LA 2018, PyData NYC 2018, PyData Delhi 2018, SciPy 2018, PyCon US 2018, PyData London 2018, PyData NYC 2017, PyConDE 2017, PyCon PL 2017, EuroSciPy 2017, EuroSciPy 2016, SciPy India 2015 and is a part of (notebooks 7 and 8) Eric Ma's tutorial Network Analysis made Simple https://github.com/ericmjl/Network-Analysis-Made-Simple

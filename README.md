# PyData London 2018 NetworkX

NOTE: This repo will be updated before the tutorial so make sure to pull new changes.

### Set Up

For this tutorial, you will need Python3 and the following packages:

- `networkx`
- `pandas`
- `matplotlib`
- `numpy`
- `jupyter`

Python2 may/may not work, no promises :)

### Clone/Download the repo

- `$ cd /path/to/your/directory`
- Clone the repository from GitHub
	 `$ git clone https://github.com/mriduls/pydata-networkx`
- `$ cd pydatanyc-2017-networkx`

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

### Credits

This tutorial is inspired by the previous offerings of this tutorial at PyData NYC 2017, PyConDE 2017, PyCon PL 2017, EuroSciPy 2017, EuroSciPy 2016, SciPy India 2015 and Eric Ma's tutorial Network Analysis made Simple https://github.com/ericmjl/Network-Analysis-Made-Simple

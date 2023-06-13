# pH Glider Tutorials
Jupyter Notebook tutorials for downloading, plotting and analyzing pH glider data.

[Rutgers University Center for Ocean Observing Leadership](https://rucool.marine.rutgers.edu/)

Author: Lori Garzio (lgarzio@marine.rutgers.edu)


## Installation Instructions
Add the channel conda-forge to your .condarc. You can find out more about conda-forge from their website: https://conda-forge.org/

`conda config --add channels conda-forge`

Clone the phglider-tutorials repository.

`git clone https://github.com/rucool/phglider-tutorials.git`

Change your current working directory to the location that you downloaded phglider-tutorials. 

`cd /Users/lgarzio/Documents/repo/phglider-tutorials/`

Create conda environment from the included environment.yml file:

`conda env create -f environment.yml`

Once the environment is done building, activate the environment:

`conda activate phglider-tutorials`

To activate the jupyter notebook:

`jupyter notebook`

This will start a Jupyter notebook server in a browser window. You can then run and modify the notebooks.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/COMPUTE-Jupyter-course/project-for-compute-jupyter-2022-MargotK25.git/HEAD)

**How to run the Jupyter Notebook**

**Option 1: Binder**

View this Jupyter Notebook through Binder. Just click on the Binder badge and run the Jupyter Notebook. Note that the instructions about how to run the Jupyter Notebook and how to set the home directory of R are only relevant if you want to run a downloaded copy (see option 2).


**Option 2: Download and run (instructions for Windows)**

Download the Jupyter Notebook file (FLUXNET_LPJGUESS.ipynb), the .yml file (environment.yml) and the required data (Jupyter_FLUXNET_LPJGUESS.RData and msnowdepth.out).

Make sure you have installed either minconda3 or anaconda3.

Open the anaconda prompt and navigate to the folder where you have saved the .yml file.

Install the new environment by running:  conda env create -f environment.yml 

Next activate the new environment by running:  conda activate FLUXNET_LPJGUESS 

Open Jupyter notebook by running:  jupyter notebook 

Some Python modules need to be imported and various R packages have to be installed. For further instructions, see the Jupyter Notebook file.

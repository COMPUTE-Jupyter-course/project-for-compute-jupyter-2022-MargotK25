How to run the Jupyter Notebook 

Download the Jupyter Notebook file (FLUXNET_LPJGUESS.ipynb), the .yml file (environment.yml) and the required data (Jupyter_FLUXNET_LPJGUESS.RData and msnowdepth.out).

Make sure you have installed either minconda3 or anaconda3.

Open the anaconda prompt and navigate to the folder where you have saved the .yml file.

Install the new environment by running:  conda env create -f environment.yml 

Next activate the new environment by running:  conda activate FLUXNET_LPJGUESS 

Open Jupyter notebook by running:  jupyter notebook 

Some Python modules need to be imported and various R packages have to be installed. For further instructions, see the Jupyter Notebook file.

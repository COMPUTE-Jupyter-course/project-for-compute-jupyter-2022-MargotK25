**Based on the comments from my peer, I have made the following changes:**
1. I have added the possibility to run the Jupyter Notebook with Binder. This was not that straightforward as it is rather dependent on various R packages, including some that are not available through Anaconda/pip.  Most packages will be installed when launching Binder (hence it takes quite some time before the Noteboook is ready) but some packages still have to be installed when running the Notebook. I also had to solve the issue with the home directory of R when using Binder. It should now no longer be necessary to change the path when using Binder.

2. I have updated the README file with a Binder badge and clarified that the other instructions (downloading the files) is meant for Windows computers.

3. I have not made any changes regarding the comments about pandas/numpy. The reason for this is that I have used equivalent packages, but in R instead of Python.

## Installation

To use this project, you need to have `conda` installed on your system. It is recommended to use miniconda.

1. Clone this project or download the project onto your local machine
2. Navigate to this directory on the command line
3. Create the conda environment with the following command:
```commandline
conda env create -f ARU_CWS_env.yml -n ARU_CWS_analysis
```
* you may need to install conda: https://www.anaconda.com/download/
* and add it to your path variables - follow fix 3. https://www.partitionwizard.com/partitionmanager/conda-is-not-recognized.html
4. Activate the newly created conda environment
```commandline
conda activate ARU_CWS_analysis
```
5. Now, install the jupyter kernel by entering the following commands:
```commandline
conda install ipykernel -y
python -m ipykernel install --user --name=ARU_CWS_analysis 
```
6. Start a Jupyter server so you can open the included notebooks (`*.ipynb`). Note this will start an ongoing process that needs to stay open to keep the server running.
```commandline
jupyter lab
```
7. Select the newly installed kernel via the Jupyter notebook web UI. This can be found by selecting "Kernel" in the toolbar at the top, then selecting "Change Kernel", then selecting the kernel named ARU_CWS_analysis.
8. Now the included notebooks can be used and run interactively

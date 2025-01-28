# SOM-Assignment3

## PySOMVis Setup Guide

Follow these steps to set up your environment and run PySOMVis on your local device:

1. **Create the Conda environment:** Open a terminal (or Anaconda Prompt), navigate to the directory containing the ```environment.yml```, and run the following command to create the environment:
    ```sh
    conda env create -f environment.yml
    ```

2. **Activate the environment:** Once the environment is created, activate it using:
    ```sh
    conda activate sos_pysom
    ```

3. **Install additional packages using pip:** Due to issues with installing certain packages via Conda, use pip to install them:
    ```sh
    pip install scikit-learn==1.0.2 scikit-image==0.18.3
    ```

**Note:** We do not recommend running the experiments on VSCode as we experienced issues with visualizations not displaying correctly. An alternative that worked well is using Jupyter Notebook in the browser.
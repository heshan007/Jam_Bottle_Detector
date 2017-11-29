# Jam_Bottle_Detector

## Steps For Iinstalling Dependancies

- *Install Anaconda*
Install Anaconda latest version (python 3.6) for windows from [here](https://www.anaconda.com/download/#linux)

- *Install Tensorflow*
Run command `pip install tensorflow` in the command prompt

- *Install Keras*
Run command `pip install Keras` inthe command prompt

This steps installs the CPU version of Keras which may be slow in implenting the detector. But it is easier to setup than the GPU version, which involves in installing CUDA dependencies, only possible if .you have a CUDA compatible GPU.

Now you can run the notebook that contain the detecor

## Using the Notebook

- Go to the directory that contains the notebook using command prompt
- Run command `jupyter notebook`
- Now a browser page will load containg the files and directoris (including the notebook).
- Click the notebook
- Now you can run the cells in the notebook. [Here](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#notebook-user-interface) is a guide for running notebooks

## Weights

- Weights for the model used in detecting is given in the file `weights_500_2000000_60`.
- This is loaded in to the model when you run the notebook.

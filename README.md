# Jam_Bottle_Detector

First a conda environment with needed dependencies should be set-up to run the detector. Use the CPU or GPU versions approach dpeending on the feesibility of implimenting them in your system.

## Steps For Iinstalling Dependancies (CPU version)

1. **Install Anaconda**

- Install Anaconda latest version (python 3.6) for windows from [here](https://www.anaconda.com/download/#linux)

2. **Create a conda environment**

- This environment will be used to install Keras. A guide for creating and using conda environments is given [here](https://conda.io/docs/user-guide/tasks/manage-environments.html)
 - Next steps involving installing tensorflow and keras should be done after activating the environment you created. Activating conda environments is explained in the above guide.
 - The notebook should also be run in this envrionment.

3. **Install Tensorflow**

- Run command `pip install tensorflow` in the command prompt

4. **Install Keras**

- Run command `pip install Keras` in the command prompt

This steps installs the CPU version of Keras which may be slow in implenting the detector. But it is easier to setup than the GPU version, which involves in installing CUDA dependencies, only possible if .you have a CUDA compatible GPU.

## Steps For Installing Dependancies (GPU version)

1. **Follow step 1 and 2 in the CPU version guide**

2. **Install Tensorflow GPU version**

- A guide for installing tensorflow gpu version is given [here](https://www.tensorflow.org/install/install_windows).
- Should be careful when installing cuda toolkit and cudnn library.

3. **Install Keras**

- Same as the step 4 of CPU version guide.

Afetr installing dependencies in either way given above, you should install `dill` in your environment. This is needed to read the pickeld images .
For this simply run `pip install dill` in the command prompt after activating the environment.
Now you can run the notebook that contains the detecor

## Using the Notebook

- Go to the directory that contains the notebook using command prompt
- Run command `jupyter notebook`
- Now a browser page will load containg the files and directoris (including the notebook).
- Click the notebook
- Now you can run the cells in the notebook. [Here](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#notebook-user-interface) is a guide for running notebooks

## Weights

- Weights for the model used in detector is given in the file `weights_500_2000000_60` (Not included here).
- Copy the weights file to the directory of the notebook.
- This is loaded in to the model when you run the notebook.

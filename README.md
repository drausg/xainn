# Explainability of neural networks based on their architecture
This github repository works as a platform for my Master's thesis, Explainability of neural networks based on their architecture.
The dataset used in this study is CIFAR-10 dataset from Learning Multiple Layers of Features from Tiny Images, Alex Krizhevsky, 2009.
The code may require some tweaking to actually perform, especially to get the paths down correct. For the most part one can simply go from top to bottom in a sequence once the data is present, and the code blocks will provide some neat steps.

# Requirements
The code requires the following libraries to run:
### (py)torch
### numpy
### torchvision
### matplotlib
### CUDA
### cudnn
### SHAP
### LIME
### JUPYTER-LAB / JUPYTER-NOTEBOOK

The installation guide for Pytorch and torchvision can be found from the pytorch website https://pytorch.org/.
Cuda toolkit can be found at https://developer.nvidia.com/cuda-toolkit
Matplotlib, shap, lime and jupyter-lab / jupyter-notebook can be installed via anaconda using conda install {package}.

# Usage
Set up jupyter-notebook / jupyter-lab so that the libraries are loaded in. This can be done by creating a conda/python environment with the prerequisites, activating that environment and then running jupyter. 
Once the jupyter-notebook instance is running, open XAINN.ipynb and run each block one at a time, starting from the top. 

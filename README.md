# CS231n: Convolutional Neural Networks for Visual Recognition 
## Stanford / Winter 2024

This repository contains my assignment solutions of the Stanford CS224N: Natural Language Processing with Deep Learning course.



## Environment Setup
If you have Conda installed in your computer, follow these steps, to setup the environment.

#### 1. Create an environment with dependencies specified in environment.yml:  
    conda env create -f environment.yml
#### 2. Activate the environment:
    conda activate cs224n_env
#### 3. Inside the new environment, instatll IPython kernel so we can use this environment in jupyter notebook: 
    python -m ipykernel install --user --name cs224n_env
#### 4. Homework 1 (only) is a Jupyter Notebook. With the above done you should be able to get underway by typing:
    jupyter notebook assignment1/exploring_word_vectors.ipynb
#### 5. To make sure we are using the right environment, go to the toolbar of exploring_word_vectors.ipynb, click on Kernel -> Change kernel, you should see and select cs224n_env in the drop-down menu.
#### To deactivate an active environment, use
    conda deactivate
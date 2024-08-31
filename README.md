# Intro

Introduction to concept of project, what it solves

# Setting it up

Ensure you have python 3.9

Create a project on GitHub
git clone into convenient location

in terminal, cd into your project

python -m venv NAME

.\NAME\Scripts\Activate

pip list should show 2 things

pip install ipykernel

python -m ipykernel install --name=NAME

pip install tensorflow==2.8 tensorflow-gpu==2.8 matplotlib==3.3.4 opencv-python==4.5.5.64 numpy==1.22.3

install CUDA version 11.2.2

install CuDNN version 8.1.1, extract, then copy contents from each folder to respective folder in User/Program Files/NVIDIA GPU Computing Toolkit/CUDA folder

jupyter lab

------------------

# Setting up Data

Once you find a dataset you are comfortable with using as your data, you must set it up properly

Whether performing a classification or regression task, setup your data directory such that the classes are 


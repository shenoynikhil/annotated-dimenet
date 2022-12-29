# Annotated DimeNet
A blog going over the construction of DimeNet in a step-by-step manner.

To run this in your setup, consider doing the following,
```bash
# create conda environment
conda create -n annotated-dimenet python=3.8
conda activate annotated-dimenet

# install pytorch (could vary based on the cuda version you have)
conda install pytorch torchvision pytorch-cuda=11.6 -c pytorch -c nvidia

# install pyg (based on the pytorch and cuda version you have)
pip install pyg-lib torch-scatter torch-sparse -f https://data.pyg.org/whl/torch-1.13.1+cu116.html
pip install torch_geometric

# install sympy
conda install sympy

# install jupyter
pip install jupyter
```

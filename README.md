# PyTorch-References

## Setup Anaconda on server:

Download [Anaconda installer](https://repo.anaconda.com/archive/Anaconda3-2021.11-Linux-x86_64.sh)

```
$bash Anaconda3-xxxx-Linux-x86_64.sh
```
Ref: [linux install](https://docs.anaconda.com/anaconda/install/linux/#)


#### Creating conda environment:
```
$conda create -n pytorch
```
Activate env on every fresh login
```
$conda activate pytorch 
```
Ref: [Manage conda env](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#)

## Installing packages within the conda environment


Install libraries like ```numpy, sklearn, matplotlib, opencv``` as
```
$conda install numpy
```
OR
```
$pip install numpy
```
PyTorch: [ref](https://pytorch.org/get-started/locally/)
```
conda install pytorch torchvision cudatoolkit=11.3 -c pytorch
```


## Python tutorial

Ref: [CS231n python tutorial](https://cs231n.github.io/python-numpy-tutorial/)

## Pytorch

Quick intro [PRNN ref](some_resources_prnn.pdf)

More detailed ref on tensors, dataloaders etc. [CS231n pytorch tutorial](cs231n_PyTorch_tutorial.pdf)


**Other References:**

- [Pytorch official tutorial on transfer learning pipeline](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html#)
- [Pytorch basics](https://pytorch.org/tutorials/beginner/basics/intro.html)

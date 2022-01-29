# PyTorch-References

### Setup Anaconda on server:

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

PyTorch:
```
conda install pytorch torchvision cudatoolkit=11.3 -c pytorch
```

Other libraries often used: numpy, sklearn, matplotlib,  


## Python tutorial

Ref: [](https://cs231n.github.io/python-numpy-tutorial/)

## PyTorch

Quick intro: [PRNN ref](some_resources_prnn.pdf)

More detailed tutorial: [CS231n ref]


Ref: [](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html#)

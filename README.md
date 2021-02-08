# LGP-GNN
Downloadable code for the experiments in the paper "Graph Neural Networks with Local Graph Parameters"

Steps to run code:
1. Install dependencies from requirements.txt (or requirements_cpu.txt). We advisse creating a separate environmnet using the conda environment.

```
        conda create --name <env_name> --file requirements.txt
        conda create --name <env_name> --file requirements_cpu.txt
```

> :warning: **These installs of pytorch (1.6.0) and dgl (0.5.3) will work for CUDA 10.1**: If you have another version of the cuda-toolkit on your system or device you should get the corresponding versions and change the requirements file accordingly. E.g. to "dgl-cu100" and "torch==1.6.0+cu100". 
   
2. Download the datasets

....
 
> :warning:  All the different versions of all datasets will take up a lot of space on your disk. Separate links are provided for every dataset.

3. Get the train-val-test pipeline running as in one of the notebooks. Examples are provided to reproduce the best results for every dataset. The notebooks are also provided as plain .py scripts.

Please reach out to <lgpgnn2021@gmail.com> for questions and remarks.


# TTK4260-MULTIVAR_ANALYSIS

This repository contains exercises from the course Multivariate Data Analysis and Machine Learning (TTK4260)

## Activating environment

An "environment.yml" file is included in the repository which contains all packages requires to run code within this repository. Create the environment by executing the following in shell,

```bash
conda env create --file environment.yml
```

then activate with,

```bash
conda activate ttk4260
```

If the environment.yml file has been updated, apply the new changes to existing environment by executing,

```bash
conda env update --file environment.yml --prune
```

### PyTorch

This needs to be installed seperately through,

```bash
conda install pytorch==1.8.0 cpuonly -c pytorch
```
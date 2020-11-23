
Jupyter Notebooks and Dotnet
=================================

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MattSheehanDev/jupyter-notebooks-dotnet/HEAD)

Setup
-----------------------------

Download and Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) and [.NET](https://dotnet.microsoft.com/download)

Install JupyterLab
```
conda install -c conda-forge jupyterlab
```

Install dotnet interactive and dotnet jupyter kernel
```
dotnet tool install -g microsoft.dotnet-interactive

dotnet interactive jupyter install
```


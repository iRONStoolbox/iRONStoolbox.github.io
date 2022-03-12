---
title: Install
nav: true
---

[<img src="iRONS_logo_6.png" alt="iRONS logo" style="width:30%;" >](./Install.md/)

## Installing iRONS locally

Our recommendation is that you use the Anaconda distribution to install both Python and the Jupyter Notebook locally. 

Use this link https://www.anaconda.com/download/ to install the Anaconda distribution. It includes a number of useful packages and is much easier than managing packages individually. Choose the Python 3.6 version or above depending on your operating system.

Alternatively, if you already have Python you will only need to download Jupyter Notebook by running:

```
pip install notebook
```

### How to download iRONS and run it locally

Open the Anaconda Prompt from the Windows menu (or a OS Terminal in Mac and Linux), and then run:
```
conda update conda
```

[<img src="iRONS_logo_6.png" alt="iRONS logo" style="width:30%;" >](./Install.md/)

To download iRONS you can either click on Clone button that you will find in the iRONS Github repository or you can run this on the Anaconda Prompt:
```
git clone https://github.com/AndresPenuela/iRONS.git
```
Once the download is finished, in the Anaconda Prompt get into the local iRONS folder:
```
cd iRONS
```
Now create an environment and install all dependencies (necessary libraries to run iRONS):
```
conda env create -f environment.yml --prefix irons_env
```
Then you need activate the environment:
```
conda activate ./irons_env
```
Now you need to run Jupyter Notebooks to use iRONS locally:
```
jupyter notebook
```
If you need to remove the environment beacuse you are not going to use iRONS locally anymore, first you need to deactivate the environment:
```
conda deactivate ./irons_env
```
And then remove the environment:
```
conda remove --all --prefix "./irons_env"
```
If you use JupyterLab instead of Jupyter Notebook you will need to install the following extensions:
```
jupyter labextension install @jupyter-widgets/jupyterlab-manager # install the plotly extension
jupyter labextension install bqplot@0.4.6 # install the bqplot extension
jupyter labextension install @jupyterlab/plotly-extension # install the Jupyter widgets extension
```
## Testing

The easiest way to test if the current version of iRONS is working is to check that this icon shows "build passing"
[![Build status](https://travis-ci.org/AndresPenuela/iRONS.svg?branch=master)](https://travis-ci.org/AndresPenuela/iRONS)

If you have downloaded iRONS and you are using it locally you can run manually the test functions. First you need to install `pytest`. For that purpose open the Anaconda Prompt and then run:
```
pip install -U pytest
```
now, from the local iRONS folder, invoke `pytest` through the Python interpreter from the command line:
```
python -m pytest
```

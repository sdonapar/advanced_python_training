# Data Analysis Using [Python](https://www.python.org) - Environment Setup

## Install miniconda

- Download [Miniconda](https://docs.conda.io/en/latest/miniconda.html) based on your operating system
- Install Miniconda, please accept the default directory suggested by the installer

## Configure conda environment

- Add conda-forge channel
``` bash
conda config --show
conda config --show channels
conda config --add channels conda-forge
```
- Optional Setp: Add following proxy_server settings if necessary. Please change the values "http://user:pass@corp.com:8080" and "https://user:pass@corp.com:8080" 
```bash
conda config --set proxy_servers.http http://user:pass@corp.com:8080
conda config --set proxy_servers.https https://user:pass@corp.com:8080
```

## Create virtual environment

- Create virtual environment by name "training" using following command
``` bash
conda create -n training python=3.7
```
- Activate the environment
```bash
conda activate training
```

## Install IDE
- Download [Visual Studio Code](https://code.visualstudio.com/download), better to use "User Installer"
- After installing Visual Studio Code, install "Python" [Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) provided by Microsoft




**A repository created to track my FastAI's course journey**

## Conda installation - Windows 11 (Using WSL) ##

1) Open the Microsoft Store and install the latest Ubuntu distribution.

2) Open an Ubuntu terminal and run:
```powershell
wget "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"
bash Miniforge3-$(uname)-$(uname -m).sh
```
PS: Instructions for the above can also be found [here]:(https://github.com/conda-forge/miniforge).

3) Restart your Linux terminal (otherwise, the "conda" command won't be found).

4) Run the following command once:
```powershell
conda init
```

5) Update conda:
```powershell
conda update -n base -c conda-forge conda
```

6) Create a virtual environment called "fast_ai":
```powershell
conda create -n fast_ai
```
7) Switch to the newly created environment:
```powershell
conda activate fast_ai
```
8) Check the **fast_ai** environment is selected (there will be a * next to it):
```powershell
conda info --envs
```

## pip installation ##
```powershell
conda install pip
pip --version
```

## JupyterLab installation and execution ##
```powershell
pip install jupyterlab
jupyter lab
```

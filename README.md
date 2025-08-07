**A repository created to track my FastAI's course journey**

## Conda installation (Windows 11) ##

1) Go to [conda-forge](https://conda-forge.org/download/) and download the latest version of Miniforge3 (.exe).

2) Once installed, add **C:\Users\yourUser\miniforge3\condabin** to your ***PATH***

3) Update conda:
```powershell
conda update -n base -c conda-forge conda
```
4) Run the following command once:
```powershell
conda init
```
5) Create a virtual environment called "fast_ai":
```powershell
conda create -n fast_ai
```
6) Switch to the newly created environment:
```powershell
conda activate fast_ai
```
7) Check the fast_ai environment is selected (there will be a * next to it):
```powershell
conda info --envs
```

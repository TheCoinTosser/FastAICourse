################
# FastAICourse #

A repository created to track my FastAI's course journey

###############################
## Installation (Windows 11) ##

1) Go to https://conda-forge.org/download/ and download the latest version of Miniforge3 (.exe).

2) Once installed, add C:\Users\yourUser\miniforge3\condabin to your PATH

3) Update conda
conda update -n base -c conda-forge conda

4) Run the following command once:
conda init

5) Create a virtual environment called "fast_ai"
conda create -n fast_ai

6) Switch to the newly created environment
conda activate fast_ai

7) Check the fast_ai environment is selected (there will be a * next to it)
conda info --envs

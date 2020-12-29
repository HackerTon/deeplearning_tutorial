## Operating System, Software and Hardware Requirements
* Operating system: Windows 10
* RAM: Recommended 8GB
* Disk space: 5GB-10GB
* Python

## Preparing installation
1. Download the repository by downloading as ZIP
2. Extract the zip with `Extract here`
3. Copy the folder `deeplearning_tutorial-master` to `Documents`

## Creating the `Conda` environment for the IMachine Workshop
1. Download and install [Anaconda](https://repo.anaconda.com/archive/Anaconda3-2020.11-Windows-x86_64.exe) or [Anaconda (32bit)](https://repo.anaconda.com/archive/Anaconda3-2020.11-Windows-x86.exe)
2. Change directory to user documents with `cd Documents\deeplearning_tutorial-master`
2. Make sure conda is in the system `PATH` by running command `conda --version` in the command prompt
3. Create a conda virtual environment using `conda create -n workshop-im`
4. cd into the `<project directory>`
5. Activate the newly created environment with conda activate workshop
6. Install the required libraries by typing the following in the command prompt
7. Use: `pip install -r requirements.txt`

## Activating `conda` environemnt
1. Activate the newly created environment with `conda activate workshop-im`
2. If successfully activated, your command prompt should show you `(workshop-im) C:\Users\X\Documents\deeplearning_tutorial-master`, instead of showing `C:\Users\X\Documents\deeplearning_tutorial-master`

## Validating Jupyter notebook works
1. Go to your code directory and activate the conda environment in the command prompt
2. Next, to run jupyter notebook type `jupyter notebook`
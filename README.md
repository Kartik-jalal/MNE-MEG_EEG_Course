# MNE-MEG_EEG_Course
This Repo is for working through the [MEG+EEG analysis and visualisation course by MNE](https://mne.tools/stable/auto_tutorials/index.html), to help me familiarise myself with brain data and the workings around it.


## Setup

A combination of *JupyterNotebooks* and *Python venv* are used as the setup enviornment. To create a *Python `venv`*, run the following command inside this repo dir:
```bash
python3 -m vevn .venv
```
Then, activate the `venv` simply by:
```bash
source .venv/bin/activate
```
Now, install the required *python libs* by:
```bash
pip install -r reqs.txt
```

Lastly, to deactive the `venv` simply run:
```
deactivate
```

Now everytime you open any of the jupyter notebooks simply select the *Kernel* '__.venv (Python {version})__' using the '*Select Kernel*' option.

# Chapters

## [Chapter 1 | Introductory Tutorials](https://mne.tools/stable/auto_tutorials/intro/index.html) - [Notebook](chapter_1.ipynb)
In chapter 1, we have so far looked at the overview of MEG/EEG analysis with MNE-Python.



# Latest Update
### 20th of Aug, 2025 
- Completely updated the [`req.txt`](reqs.txt), please first `deactivate` the python `venv`, then remove the the `.venv` setup by running `rm -rf .venv`, and then perform the [setup procedure again](#setup).

- Added [chapter_1.ipynb](chapater_1.ipynb) with the overview section of MEG/EEG analysis.


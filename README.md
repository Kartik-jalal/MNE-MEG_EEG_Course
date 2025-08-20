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
> _Note: The `reqs.txt` also installs `pip-tools` lib, so whenever there will be an update in the `reqs.txt` file simply run `pip-sync reqs.txt` to update the venv with the right *python libs*.

Lastly, to deactive the `venv` simply run:
```
deactivate
```

Now everytime you open any of the jupyter notebooks simply select the *Kernel* '__.venv (Python {version})__' using the '*Select Kernel*' option.

# Latest Update
### 20th of Aug, 2025
- Added new python libs to `reqs.txt` file, please run the command `pip-sync reqs.txt` in the python venv to update it.
### 19th of Aug, 2025
- Added the `reqs.txt` file
- Added the setup section in the `README.md`.


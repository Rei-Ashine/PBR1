# PBR1
Author: rei-ashine<br>
DATE: Dec. 21st, 2023<br>

---
Scripts for
01. Formatting a PDB file<br>
USAGE: `bash 01_format_pdb_files.sh &>> logs/formatting.log`<br>
[NOTE]: Before running the shell script,<br>
you should do `cp config.sample config` and change the path<br>
to the directory containing the pdb files you want to format in the config file.

---
## Installing Dependencies
All dependencies can be installed with conda.<br>
An environment screenshot is provided :
```bash
conda env create -f environment.yml
```
Once the environment is created,<br>
it can be used at any time (without having to download everything again) :
```bash
conda activate pbr1
```
Exit the running virtual environment :
```bash
conda deactivate
```
Delete the virtual environment :
```bash
conda remove -n pbr1 --all
```

## Setting up Jupyter Notebook
Add a virtual environment to the kernel of Jupyter Notebook :
```bash
ipython kernel install --user --name pbr1
```
Confirm that "pbr1" is included in "Available kernels" :
```bash
jupyter kernelspec list
```

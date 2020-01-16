# JupyterMS
> Mass spectrometry visualisation in a Jupyter notebook

JupyterMS is a notebook for quick interactive visualisation of MS1 spectra from mzML files   
Try the notebook with binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pierrepo/JupyterMS/master)

## Quick-start

Install [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)  

Clone the repository:
```shell
$ git clone https://github.com/pierrepo/JupyterMS
$ cd JupyterMS
```

Create conda environment:
```shell
$ conda env create -f environment.yml
```

Remark: for a fully reproducible environment, you could also use:
```shell
$ conda env create -f environment.lock.yml
```

Activate conda environment:
```shell
$ conda activate JupyterMS
```

Activate jupyter:
```shell
$ jupyter notebook
```
then go in the *notebooks/* folder and open *MS_visualisation.ipynb*  
You can place the mzML file in the *data/* folder and link it to the notebook
by modifying the `mzml_file` variable

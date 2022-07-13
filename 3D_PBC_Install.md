## Instructions for installing the **beta** 3D/PBC *tobac* code

While 3D and periodic boundary support will be included in *tobac* v1.5 (releasing summer-fall 2022), it is available now as a beta release. As this is in beta, there may be bugs. If you find any, we encourage you to contact us (sean.freeman (at) colostate.edu or g.alex.sokolowsky (at) colostate.edu). Instructions for installing this beta release are below.

### Getting Anaconda
While Anaconda isn't required to use *tobac*, if you are new to python, it will make things easier. You can download anaconda (here)[https://www.anaconda.com]

### Creating a new conda environment
While this step is not required, it is *strongly* encouraged. If you do not create a new conda environment, you could end up causing conflicts if the release version of *tobac* is still installed. 
```
conda create --name tobac_15
```

You then must activate this environment:
```
conda activate tobac_15
```

### Installing the required packages
You can use either `conda` or `mamba` to install your packages. While we recommend `mamba` due to its vastly superior speed, you will have to install that separate: `conda install -c conda-forge -n base mamba`. 

You can then install the requirments by: 

```
mamba install -c conda-forge numpy scipy scikit-image pandas pytables matplotlib iris cf-units xarray cartopy trackpy scikit-learn
```

### Installing the v1.5 beta
Download the v1.5 beta from here: (https://github.com/galexsky/tobac/archive/refs/heads/dev-3D-PBC-support.zip)[https://github.com/galexsky/tobac/archive/refs/heads/dev-3D-PBC-support.zip]. Once it's downloaded, unzip it and go into the directory. Then, to install:

```
pip install .
```


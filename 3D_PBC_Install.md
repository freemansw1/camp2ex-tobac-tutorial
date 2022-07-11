## Instructions for installing the **beta** 3D/PBC *tobac* code

While 3D and periodic boundary support will be included in *tobac* v1.5 (releasing summer-fall 2022), it is available now as a beta release. As this is in beta, there may be bugs. If you find any, we encourage you to contact us (sean.freeman (at) colostate.edu or g.alex.sokolowsky (at) colostate.edu). Instructions for installing this beta release are below.

### Creating a new conda environment
While this step is not required, it is *strongly* encouraged. If you do not create a new conda environment, you could end up causing conflicts if the release version of *tobac* is still installed. 
```
conda create --name tobac_15
```

### Installing the required packages
You can then install the requirments by: 
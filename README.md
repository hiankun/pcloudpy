# pcloudpy ![](resources/pcloudpy_icon.png)

## NOTE
The status of this toolkit based my own tests is:

* supports only Python 2.7
* tested in Ubuntu 16.04 and Python 2.7 environment created using Anaconda
* the installation was successful but the GUI app still has problems

## Installation in Anaconda environment

You may use the `py2_env.yml` as a reference to install the dependencies.

## Usage

### normal approach (it'll fail)
In the Python shell or script, type

```
import pcloudpy
pcloudpy.gui.app.run()
```

### not-so-correct appraoch (you can see the GUI but it still cannot open PLY files)
Found `main.py` in the source foler and run `python main.py`.

--------
[Original README.md is as follows...]

Point Cloud Viewer and Processing Toolkit in Python


This toolkit aims at providing an ease interface to display point clouds in many formats and performing diverse filtering processes. 
This project goal is to make use of amazing libraries such as numpy, scipy, matplotlib, IPython, VTK, pandas, sklearn, laspy, pyside, pyqode and so on to be used in the display and processing of point clouds.
**pcloudpy** project is highly inspired in Paraview, MeshLab, CloudCompare, FreeCad, PCL.  It attempts to offer an alternative to add modules written in python easily. 
An IPython Console and a Python Editor are also available in order to interact with the pcloudpy api and graphical user interface.


-------

The main features of the pcloudpy module are the following:

- Display dense point clouds
- Selection and Cleaning of point clouds
- Filtering of point clouds (point neighborhood statistics, Outlier removal)
- Extent Extraction from Point Clouds
- Delaunay Triangulations
- Normals Estimation (PCA Eigen Method & Oriented)
- Screened Poisson Surface Reconstruction
- Interaction with pcloudpy modules from an embedded IPython Console

-------

![](https://github.com/mmolero/pcloudpy/blob/master/resources/pcloudpy_v0.10.png)

------

Requirements:

- VTK==5.10.1

- GDAL>=1.11.0

- markdown2>=2.3.0

- laspy>=1.2.5

- PyYAML>=3.11

- pyqode.core>=2.6.6

- pyqode.qt>=2.6.0

- pyqode.python>=2.6.3
 
- pypoisson, see https://github.com/mmolero/pypoisson



-----

if you are interesting in collaborating and/or testing this software, please don't hesitate to contact me

------


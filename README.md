# Resbaz-Syd-21-Putting-Your-Data-On-the-Map
This is the repository with code, data and the powerpoint to follow along with Jonathan Garber's "Putting your Data on the map: An introduction to Geospatial data"

## Running the notebook on google collab
You can run the Jupyter notebook on google collab here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sailngarbwm/Resbaz-Syd-21-Putting-Your-Data-On-the-Map/blob/main/Intro%20to%20GIS%20and%20python.ipynb)

## Running the code on your own machine
To run the notebook on your own computer you need to run the following commands after cloning the library 

### Using conda
If you are managing your python environments with conda then run the following commands.

#### Creating a conda environment

run the following command to create and activate a conda environment

```bash
conda create -n gis_env python=3.8 
```

Followed by the following commands:

If you are on a mac/ linux machine:

```bash
conda activate gis_env
```

If you are on a windows machine in the anaconda prompt:

```bash
activate gis_env
```

#### After creating an environment

```bash
conda install -c conda-forge proj=8.0
```
then
```bash
pip install -r requirements
```

Then you can run a jupyter notebook:

```
jupyter notebook
```


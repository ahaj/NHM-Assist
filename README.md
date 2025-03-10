# NHM-Assist
NHM-Assist is a collection of python workflows presented in Jupyter notebooks for evaluating, running and interpreting [National Hydrologic Model (NHM)](https://www.sciencebase.gov/catalog/item/626c0d67d34e76103cd2ce4a) domains using [pywatershed](https://github.com/EC-USGS/pywatershed). NHM-Assist allows users to:
- evaluate hydrofabric element connections such as hydrologic response unit connections to streamflow segments, segment routing order, and gage placement accuracy;
- display NHM domain parameter values on interactive maps and plots;
- run the NHM domain using pywatershed and create output for chosen variables;
- display NHM domain output values, such as recharge or actual evapotranspiration, on interactive maps and plots; and
- display simulated and observed streamflow for model gages on interactive plots.

Select interactive maps and plots generated by NHM-Assist are saved locally in .html format and displayed in a web browser.



## Install conda-forge miniforge on your PC
Instructions for standard installation of conda-forge miniforge is available at this [link](https://github.com/conda-forge/miniforge)
For USGS users, it is recommended to use the agency ???


## Build the environment
Open a miniforge prompt.

If the `nhm` environment already exists, then remove it: 
```
conda remove -y --name nhm --all
```

Install a fresh env:
```
conda env create -f environment.yaml
```
## 1/8/25 note: need to run 'python pull_domain.py --name=willamette_river' in the command window from the repo to get the example/sample model

## Activate the environment:
```
activate nhm
```


## Launch Jupyter

```
jupyter lab
```

Ready to go! :+1:

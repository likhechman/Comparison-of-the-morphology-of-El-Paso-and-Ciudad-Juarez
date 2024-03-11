# Comparison of the morphology of El Paso and Ciudad Juarez
Code repository for the **Comparison of the morphology of El Paso and Ciudad Juarez** paper.

> Kaluzhak A. D. Comparison of the morphology of El Paso and Ciudad Juarez - 2024

Kaluzhak A. D.<sup>1

1 Faculty of Geography and Geoinformation Technology

Contact: ddkaluzhak@edu.hse.ru

Date: 11/03/2024

The online interactive maps of the final classification are available at [https://martinfleis.github.io/numerical-taxonomy-maps/](https://martinfleis.github.io/numerical-taxonomy-maps/).

## Code

The code is in `code` containing cleaned reproducible
Python code for everyone willing to use the method.

### The method
The folder `code` contains generalised code for the method, that should be
reproducible on a custom data. The main notebook `main_code.ipynb` has
been updated to work with the recent releases of software. You can create the
reproducible environment to run it using `conda` or `mamba` and the `environment.yaml`
file in the `code` folder.

```
conda env create -f environment.yaml
```

You can also create a new environment `taxonomy` manually:

```
conda create -n taxonomy
conda activate taxonomy
conda config --env --add channels conda-forge
conda config --env --set channel_priority strict
conda install momepy mapclassify seaborn
```

## Data

Non-proprietary data are archived on figshare as
[10.6084/m9.figshare.16897102](https://doi.org/10.6084/m9.figshare.16897102). The
archive contains input geometry, generated geometry, all measured morphometric
characters and a final classification labels for El Paso and Ciudad Juarez.

The online interactive maps of the final classification are available at [https://martinfleis.github.io/numerical-taxonomy-maps/](https://martinfleis.github.io/numerical-taxonomy-maps/).

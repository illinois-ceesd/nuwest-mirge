# MIRGE tutorial at NUWEST 2024

[NUWEST: NNSA-University Workshop on Exascale Simulation Technologies](https://illinois-ceesd.github.io/nuwest/)

## MIRGE Presentation

Click [here](https://ssl.tiker.net/nextcloud/s/TJrMAcGZpW5spjT) to download the slides.

## MIRGE Code-Along Instructions

If you're at NUWEST: We will have instructions for a prepared Jupyter environment
to which you can simply log in.

If you missed the workshop (boo!), these commands should do the trick
(on Linux/Mac):

```
curl -L -O https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh
bash ./Miniforge3-*.sh
export CONDA=/WHERE/YOU/INSTALLED/miniforge3
$CONDA/bin/conda env create -n mirge --file nuwest-mirge/environment.yml
source $CONDA/bin/activate mirge
pip install jupyterlab
cd nuwest-mirge/demos
jupyter lab
```
... and you're off to the races!


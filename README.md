[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ericpre/STEM_simulation_demo/HEAD)

Repository to demonstrate the simulation of STEM images.

### Setup conda environment

If you don't already have a Miniconda-like distribution, we recommand to install [MambaForge](https://github.com/conda-forge/miniforge/#mambaforge)

Clone or download this repository, go the folder containing the file of this repository and run the following command line in the Anaconda command prompt (Windows) or a terminal (Linux and MacOS)

```
conda env create -n STEM_simulation --file environment.yml
```

If mamba is installed, `conda` can be replace by `mamba` for faster installation.

```
conda activate STEM_simulation
jupyter notebook
```

# Computational Photography Lab Exercises

This repository contains *ungraded* lab exercises for Computational Photography.  These projects are not submitted, but the topics may appear on the final exam.


## Notebooks

### [Image Processing & Analysis](/1-image_processing)

Introduce key parts of the numpy and OpenCV APIs with an emphasis on applications in computational photography.


### [Image Frequency Spectra](/2-frequency_spectra)

Explore image processing in the frequency domain.


### [Features, Keypoints, & Applications](/3-features_keypoints)

Implement image keypoint descriptors and experiment with [OpenSfM](https://github.com/mapillary/OpenSfM), a powerful open source tool for computing [structure from motion](https://en.wikipedia.org/wiki/Structure_from_motion).


## Setup

In order to run the lab notebooks, install [anaconda](https://www.continuum.io/downloads) for python 2.7 (**DO NOT USE THE COURSE VM**), then clone this repository and create a copy of the Computational Photography conda environment by running `conda env create -f CompPhoto.yml` from the project folder in a terminal. Anaconda will automatically install the required dependencies, then you can activate the environment with `source activate CompPhoto` (OSX/Unix/Linux) or `activate CompPhoto` (Windows). With the environment active, you can run the notebook by executing `jupyter notebook` from the terminal. The terminal will display a URL that you can copy to reach the notebook explorer which can be used to select a notebook file (i.e., a file ending in ".ipynb"). You may be prompted to select a kernel the first time the notebook runs; if so, choose the CompPhoto kernel corresponding to the environment. (If you have problems accessing OpenCV within the CompPhoto environment, try running `conda install -c menpo opencv` before running the jupyter notebook -- although it should be installed when the environment is created.)

You can edit code in any cell of the notebook, and execute each cell by clicking the "play" icon on the menu bar, or using the "shift + enter" keyboard shortcut. The output of each cell will appear inline in the notebook immediately after each cell.

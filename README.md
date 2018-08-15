# RidgeToReef

Jupyter notebooks for a binder demo in the Ridge to Reef program, August 2018

Authors: Kelly Caylor (caylor@ucsb.edu) and Natasha Krell (nkrell@ucsb.edu)

## Getting Started

To get started with the excercise, click here: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ecohydro/RidgeToReef.git/master)


## About this Repo

This repository is a set of jupyter notebooks, data, and accompanying configuration files designed to be used with the [binder](mybinder.org) system. Through Binder, these notebooks provide an executable environment, making the code immediately reproducible by anyone, anywhere.

Our analyses are built on the [Anaconda](https://www.anaconda.com/distribution/) python distribution, using [Python v.3.6](https://www.python.org/downloads/release/python-360/). 

Configuration files are stored in the `binder/` folder of this repository. The `environment.yml` file contains required python packages. Note **this file cannot be auto-generated by `conda env export`.** You must instead specify the main requirements (e.g. `numpy`, `pandas`) and their versions. 


# Acknowledgements & Disclaimer

This material is based upon work supported by the National Science Foundation under Grants No. [SES-1534544](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1534544&HistoricalAwards=false) and [SES-1360421](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1360421&HistoricalAwards=false). Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
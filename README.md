# ACM-Balances-2024

# Project Title

**Analyzing the Performance of Time Series Foundation Models for
Short-term Load Forecasting**


## Description

* In this paper, we present a benchmark study of four state-of-the-art pre-trained Time Series Foundational Models(TSFM), Lag-Llama, TimesFM ,Moirai and Chronos aiming to evaluate their performance for short-term load forecasting.

* This repository contains code to load pre-trained models and run predictions.

## Installation

''To replicate the zero-shot experiment setup used in the paper, please follow these steps:''

* Step 1: Create separate environments for each model since they have different dependencies.
* Step 2: Follow the instructions in the readme_model_name file located in the respective directory for each model to install and setup.
* Important: You'll need at least 16GB RAM to run TimesFM.



## Download Dataset

In our study we have used **BuildingsBench (Emami, Sahu, and Graf 2023)** Dataset, it is an open-source software platform designed to advance re-search in short-term load forecasting (STLF). BuildingsBench contains a large set of curated smart energy meter time series data collected from both commercial and residential buildings worldwide.

* The Dataset can be downloaded form the BuildingsBench repositary https://github.com/NREL/BuildingsBench  or can be accessed directly from https://data.openei.org/s3_viewer?bucket=oedi-data-lake&prefix=buildings-bench

Download metadata.tar.gz files to a folder on a storage device. Then, decompress all of the downloaded files. There will be a new subdirectory called BuildingsBench.  
See the README file BuildingsBench/metadata/README.md (in metadata.tar.gz) for more information about how the BuildingsBench dataset directory is organized.





# Requirement or not, that is the question!
This repository contains the replication package for the paper "Requirement or not, that is the question: A case from the railway industry".
Please cite the original paper. (Expected updates: Nov 23, 2022)

## Tool
(A running tool link will be available after our AWS account gets verified. Verification expected on Nov 30, 2022)

## Replication Package
- [REFSQ23_results.xlsx](/REFSQ23_results.xlsx) contains the obtained results of our experiments.
- [models](/models) directory should contain all the trained ML models on five folds (both on data with and without pre-processing) of the [Dronology Dataset](http://sarec.nd.edu/dronology/datasets/01/). The instructions to download the models are in the following section.
- [dronology.csv](/dronology.csv) contains the original Dronology dataset in CSV format. IDs starting with `RE` are considered requirements and all other entries are considered as non-requirements.
- [data](/data) contains the generated stratified five folds from the original Dronology dataset, both with and without pre-processing. These folds are used for cross-validation of all the pipelines.

## How to run?
1. Clone the repository
2. Download (from [here]() and [here](https://doi.org/10.5281/zenodo.7347716)) and unzip the additional material  in the `models` directory
3. Create a virtual environment with Python `3.8.10` and install the `requirements.txt` using `pip install -r requirements.txt`
4. Run the Jupyter Notebook `RorNot_Pipelines.ipynb`

## Cite as
To be updated.

## Funding
This work is partially funded by the [AIDOaRt (KDT)](https://sites.mdu.se/aidoart) and [SmartDelta (ITEA)](https://itea4.org/project/smartdelta.html) projects.
<br><img src="https://smartdelta.org/wp-content/uploads/2021/12/1500x500_170x60.jpeg" width="100" >
<img src="https://sites.mdu.se/images/18.53e5afc518094948a11572ed/1622585177018/Logga%20AIDOaRt.jpg" width="100" >

# Requirement or not, that is the question!
This repository contains the replication package for the paper "Requirement or not, that is the question: A case from the railway industry".
Please cite the original paper. (Expected updates on Nov 23, 2022)

## Tool
The best model---BERT base uncased---trained on the public dataset is deployed [here](https://www.smartdelta.org/rornot). (Tool to be available after our AWS account gets verified. Verification expected on Nov 30, 2022)

## Replication Package
- [REFSQ23_results.xlsx](/REFSQ23_results.xlsx) contains the obtained results of our experiments.
- [models](/models) directory should contains all the trained ML models on five folds (both on data with and without pre-processing) of the [Dronology Dataset](http://sarec.nd.edu/dronology/datasets/01/). The instructions to download the models are in the following section.
- [dronology.csv](/dronology.csv) contains the original Dronology dataset in CSV formate. IDs starting with `RE` are considered as requirements and all other entries are considered as non-requirements.
- [data](/data) contains the generated stratified five folds from the original Dronology dataset both with and without pre-processing. These folds are used for cross-validation of all the pipelines.

## How to run?
1. Clone the repository and download the....

## Funding
This work is partially funded by the [AIDOaRt (KDT)](https://sites.mdu.se/aidoart) and [SmartDelta (ITEA)](https://itea4.org/project/smartdelta.html) projects.
![SmartDelta](https://smartdelta.org/wp-content/uploads/2021/12/1500x500_170x60.jpeg)
![SmartDelta](https://sites.mdu.se/images/18.53e5afc518094948a11572ed/1622585177018/Logga%20AIDOaRt.jpg)

# Requirement or not, that is the question!
This repository contains the replication package for the paper "Requirement or not, that is the question: A case from the railway industry".
Please cite the original paper.

## Tool
A running tool with the best model---BERT uncased---is available [here](https://huggingface.co/spaces/SarmadBashir/REFSQ2023_ReqORNot_demo_app).

## Replication Package
- [REFSQ23_results.xlsx](/REFSQ23_results.xlsx) contains the obtained results of our experiments.
- [models](/models) directory should contain all the trained ML models on five folds (both on data with and without pre-processing) of the [Dronology Dataset](http://sarec.nd.edu/dronology/datasets/01/). The instructions to download the models are in the following section.
- [dronology.csv](/dronology.csv) contains the original Dronology dataset in CSV format. IDs starting with `RE` are considered requirements and all other entries are considered as non-requirements.
- [data](/data) contains the generated stratified five folds from the original Dronology dataset, both with and without pre-processing. These folds are used for cross-validation of all the pipelines.

## How to run?
1. Clone the repository
2. Download (from [here](https://doi.org/10.5281/zenodo.7347259) and [here](https://doi.org/10.5281/zenodo.7347716)) and unzip the additional material  in the `models` directory
3. Create a virtual environment with Python `3.8.10` and install the `requirements.txt` using `pip install -r requirements.txt`
4. Run the Jupyter Notebook `RorNot_Pipelines.ipynb`

## Cite as
`@InProceedings{10.1007/978-3-031-29786-1_8,
	author="Bashir, Sarmad
	and Abbas, Muhammad
	and Saadatmand, Mehrdad
	and Enoiu, Eduard Paul
	and Bohlin, Markus
	and Lindberg, Pernilla",
	editor="Ferrari, Alessio
	and Penzenstadler, Birgit",
	title="Requirement or Not, That is the Question: A Case from the Railway Industry",
	booktitle="Requirements Engineering: Foundation for Software Quality",
	year="2023",
	publisher="Springer Nature Switzerland",
	address="Cham",
	pages="105--121",
	isbn="978-3-031-29786-1"
}`

## Funding
This work is partially funded by the [AIDOaRt (KDT)](https://sites.mdu.se/aidoart) and [SmartDelta (ITEA)](https://itea4.org/project/smartdelta.html) projects.
<br><img src="https://smartdelta.org/wp-content/uploads/2021/12/1500x500_170x60.jpeg" width="100" >
<img src="https://sites.mdu.se/images/18.53e5afc518094948a11572ed/1622585177018/Logga%20AIDOaRt.jpg" width="100" >

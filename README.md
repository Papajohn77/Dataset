# Radius Query Performance Benchmarking Datasets

The purpose of this repository is to provide the following Jupyter Notebooks for various tasks related to benchmarking datasets:

- [Benchmarking Datasets Creation](./Benchmarking_Datasets_Creation.ipynb): Generates the main datasets to be loaded into PostGIS and MongoDB.
- [Relational Model Initialization Scripts Creation](./Relational_Model_Initialization_Scripts_Creation.ipynb): Produces the SQL scripts for loading the main datasets into PostGIS.
- [Document Model JSON Files Creation](./Document_Model_JSON_Files_Creation.ipynb): Generates the JSON files to be used by the `mongoimport` tool for loading the main datasets into MongoDB.
- [Load Testing Datasets Creation](./Load_Testing_Datasets_Creation.ipynb): Generates the load testing datasets.

## Prerequisites

- Python 3
- pip3

### Getting Started

- #### Clone Repository

  `git clone https://github.com/Radius-Query-Performance-Benchmarking/Dataset.git`

- #### Change Directory

  `cd ./Dataset/data`

- #### Download the Source Datasets

  `curl -o yelp_academic_dataset_business.json "https://zenodo.org/record/8074982/files/yelp_academic_dataset_business.json?download=1"`

  `curl -o mfp-diaries.tsv "https://zenodo.org/record/8074982/files/mfp-diaries.tsv?download=1"`

- #### Change Back to Parent Directory

  `cd ../`

- #### Install Dependencies (venv is suggested)

  `pip install -r requirements.txt`

## Author

- Ioannis Papadatos (t8190314@aueb.gr)

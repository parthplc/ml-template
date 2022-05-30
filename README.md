# Knowledge Transfer for custom Cookie-cutter,Mlflow, Data versioning with DVC Git versioning,Drift detection using Alibi-detect,Model Explanability using SHAP,Python code linter flake8 and code formatting using Black

-----------------------------------

## Getting started

* Since we are following a specific modified cookie cutter for ml-projects first download structure from here [project](https://drive.google.com/drive/folders/117FUpr-tvNRYJGuLw2XxE7vSpxX9i0rb?usp=sharing) . This would be standard practice for each project.

* Download the Zip file and unzip it and rename foldername. Then 

```
cd foldername
```

* Create a virtual env and activate it

```
python -m venv env

source env/Scripts/activate
```
* Download [requirements.txt](https://drive.google.com/file/d/1GZVDzBSC2OAp1ilGpbZHiz0LnQMW87-T/view?usp=sharing) and install dependencies.

```
pip install -r requirements.txt
```

## Data dirft detection using Alibi-detect
A small demo drift detection notebook using alibi detect is inside notebooks/drift_detection folder. The script works on 
tabular(numerical and categorical both) dataset. For different use case you can check out this [repo](https://github.com/parthplc/drifter).


## Tracking data using dvc

Now follow the steps inside data/README.md file. It contains all steps on how to setup DVC for tracking dataset
versions.
<br/>


## Mlflow experiment tracking

For a detailed walk-through on how to track model metrics ,model version download the file mlflow_end_to_end.ipynb and keep inside mlflow folder. [Link to notebook](https://drive.google.com/drive/folders/1LY8O4atzZiCQMb_7t2saLoGFxqPBlX6u?usp=sharing) and save inside notebooks folder.

Notebook folder would have three sub folders
* data_processsing
* dvc
* mlflow


<br/>

## Model Explainability using SHAP

For a detailed walkthrough on how to use SHAP for model explanability for our example on titanic dataset,check notebooks/model explanability/logisticreg_explain.ipynb. 
<br/>
If any other example like image dataset or nlp dataset checkout out this [link](https://github.com/slundberg/shap/tree/master/notebooks) for more notebook as per your use case.
## Code quality and Formatting

For documentation to use flake8 and black download the file [requirements.txt](https://drive.google.com/file/d/1nVTflC2pjufE3QLR9D_hEFTjB2M34csO/view?usp=sharing) from drive and save inside reports folder.

Follow the steps inside reports/README.md for usage.

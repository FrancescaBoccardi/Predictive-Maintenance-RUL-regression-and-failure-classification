# Predictive Maintenance: RUL regression and failure classification

The purpose of this work is to inspect different approaches to solve a predictive maintenance problem on the [Microsoft Azure Predictive Maintenance dataset](https://www.kaggle.com/datasets/arnabbiswas1/microsoft-azure-predictive-maintenance).
Experimenting with different methods and architectures, the problem is approached as a regression task through the prediction of Remaining Useful Life (RUL) and as a classification 
task to classify which component will fail in the following hours.

## Repository structure

````
.
├── data                                # five .csv containing the data used for the experiments 
|   ├── PdM_errors.csv
|   ├── PdM_failures.csv                             
|   ├── PdM_machines.csv                             
|   ├── PdM_maint.csv                             
|   ├── PdM_telemetry.csv                 
├── notebook.ipynb                      # jupyter notebook containing the project's code with comments
├── models.py                           # implementation of the models used in the project
├── utils.py                            # util functions              
├── README.md
├── requirements.txt                    # necessary installations
````

## Required installations
To install the required packages to run the project, download the ````requirements.txt```` file and run the following:

````
pip install -r /path/to/requirements.txt
````

## Authors

The project has been realized by:

* Francesca Boccardi ([FrancescaBoccardi](https://github.com/FrancescaBoccardi))
* Luigi Podda ([lupodda](https://github.com/lupodda))


## Authors

The project has been realized by:

* Francesca Boccardi ([FrancescaBoccardi](https://github.com/FrancescaBoccardi))
* Luigi Podda ([lupodda](https://github.com/lupodda))
* Matteo Nestola

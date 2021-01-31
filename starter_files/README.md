# Operationalizing Machine Learning

Microsoft provides a cloud based solution with a Machine Learning component (Azure ML service) that provides the capacity to train, develop and deploy a Machine Learning mode into product. This project used <a href='https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv'>Bank Marketing dataset</a> to train a machine learning algorithm with AutoML, deploy it and consume. In another stage, a pipeline was created, published and consumed. The approach followed in this project is as shown below;

* Authentication
* Automated ML Experiment
* Deploy the best model
* Enable logging
* Swagger Documentation
* Consume model endpoints
* Create and publish a pipeline
* Documentation

## Architectural Diagram
![](screenshots/archietecture.JPG) 

## Improving the Projects

The project can be improved further through;
* Increasing the compute instances from CPU to GPU or more advanced instance that will accelerate a faster AutoML training


## Key Steps
### Step 1 - Authentication

The authentication was automatically done on the `Project Lab - VM` 

### Step 2 - AutoML Experiment

In creating the AutoML Experiment to train and deploy the model for consumption, the `Banking dataset` was first loaded after which the experiment then created and a compute cluster created to run the classification ML experiment.

The image of the datasets, experiment, and model after the experiment below.

#### Dataset
![](screenshots/dataset.JPG) 



## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.

* Deploy infrastructure with terraform
```
terraform init
terraform plan -out terraform.plan
terraform apply terraform.plan
....
terraform destroy
```
* Copy notebook and data into Databricks cluster
* Execute all the steps from "ML End-to-End Example" notebook

#####Check concat result

![Alt text](images/Check-concat-result.jpg?raw=true "Title")

#####Explore dataset with seaborn

![Alt text](images/Explore-dataset-with-seaborn.jpg?raw=true "Title")

#####Explore correlations between features and a binary label

![Alt text](images/Explore-correlations.jpg?raw=true "Title")

#####Check dataset for na values and split it into test and train sets

![Alt text](images/Check-dataset-for-na-values.jpg?raw=true "Title")

#####Building a Baseline Model

![Alt text](images/Building-Baseline-Model.jpg?raw=true "Title")

#####Check feature importance

![Alt text](images/Check-feature-importance.jpg?raw=true "Title")

#####Registering the model in the MLflow Model Registry and transition model to production

![Alt text](images/Registering-in-MLFlow&Transition.jpg?raw=true "Title")

#####Experimenting with a new model

![Alt text](images/Experimenting-model.jpg?raw=true "Title")

#####MLFlow runs

![Alt text](images/MLFlows-run.jpg?raw=true "Title")

#####Models

![Alt text](images/Models.jpg?raw=true "Title")

#####Batch Inference

![Alt text](images/Batch-Inference.jpg?raw=true "Title")

#####Load the model into a Spark UDF. It can be applied to the Delta table

![Alt text](images/Spark-UDF.jpg?raw=true "Title")

#####Model serving

![Alt text](images/Model-Serving.jpg?raw=true "Title")
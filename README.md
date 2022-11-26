# deep Classifier Projectworkflow



1.Update config.yaml    
2.Update Secrets.yaml [Optional]    
3.Update params.yaml    
4.Update the entity     
5.Update the configuration manager in src config    
6.Update the components     
7.Update the pipeline   
8.Test run pipeline stage   
9.run tox for testing your package  
10.Update the dvc.yaml      
11.run "dvc repro" for running all the stages in pipeline

STEP 1: Set the env variable | Get it from dagshub -> remote tab -> mlflow tab(run in gibash)

export MLFLOW_TRACKING_URI=https://dagshub.com/Zeeshankhan29/DeepCNNClassifier1.mlflow \        
export MLFLOW_TRACKING_USERNAME=Zeeshankhan29 \     
export MLFLOW_TRACKING_PASSWORD=<>\
python script.py

STEP 2: install mlflow

STEP 3: Set remote URI

STEP 4: Use context manager of mlflow to start run and then log metrics, params and model



# You can run this Project on a Docker image from Anywhere on a port number 8501
```
docker pull zeeshankhan29/image_class

```

# Conclusion

```
This project can be used to Predict the image of Cat and Dog        
```
![image](https://user-images.githubusercontent.com/95518247/204089273-638b8113-00fe-4425-a005-3cf95f31b254.png)
![image](https://user-images.githubusercontent.com/95518247/204089376-ab5a7389-f84c-4b6d-b6de-141d2a717ea1.png)



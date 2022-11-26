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
export MLFLOW_TRACKING_PASSWORD=9c6177f800b11201652c3fafb6f0ee36615bec40 \
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

![img]image.png       

![img]image.png


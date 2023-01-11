# Interstellar Disaster
 
# Project Goal
- For this project passengers have been transported into another dimension, and it is our job to create multiple machine learning models to predict which passengers have been transported.

# Tools Used
- **Python, Seaborn, Pandas, Numpy, Matplotlib, Sklearn, Tensorflow, Lightgbm, and XgBoost**

# Data Pipeline
- Example pipeline used for Descision Tree Classifier

![pipeline](https://github.com/bustyAI/Interstellar-Disaster/blob/main/assets/data_pipeline.PNG)

# Outcome
- **Artificial Neural Network** performed the best
    - Training Accuracy: 81.88%
    - Testing Accuracy:  79.67%
## Loss
![Loss](https://github.com/bustyAI/Interstellar-Disaster/blob/main/assets/ann_loss.PNG)
- From the graph we can see that the training data begins to level off around 100 epochs and jumps up and down slightly. **Value: 0.3625**
- For the val_loss it rises and falls through each epoch. **Value: 0.5790**

## Accuracy
![Accuracy](https://github.com/bustyAI/Interstellar-Disaster/blob/main/assets/ann_accuracy.PNG)
- From the graph, the training accuracy begins to level off around 100 epochs with an accuracy of 81%
- For the val_accuracy it also begins to level off around 100 epochs with an accuracu of 79.67%

## Intersting Fact about Data
### CryoSleep 
![cryosleep](https://github.com/bustyAI/Interstellar-Disaster/blob/main/assets/cryosleep.png)
- We can see that majority of the passengers who were in cryosleep were transported to another dimension, compared to those who were not in cryosleep.
- This could be a correlation between passengers who were in cryosleep and transported to another dimension.

## Results of all Models

- **Artificial Neural Network:**
    - Training Accuracy: 0.8188
    - Testing Accuracy:  0.7967
    
- **Decision Tree Classifier:**
    - Training Accuracy: 1.0
    - Testing Accuracy: 0.748
    
- **Decision Tree GridSearchCV:**
    - Training Accuracy: 0.81
    - Testing Accuracy: 0.769
    
- **KNN:**
    - Training Accuracy: 0.8778
    - Testing Accuracy: 0.7488
    
- **KNN GridSearchCV:**
    - Training Accuracy: 0.810
    - Testing Accuracy: 0.7815
    
- **Logistic Regression:**
    - Training Accuracy: 0.7955
    - Testing Accuracy: 0.778
    
- **Gradient Boosting:**
    - Training Accuracy: 0.831
    - Testing Accuracy: 0.794
    
- **XG Boost:**
    - Training Accuracy: 0.953
    - Testing Accuracy:  0.790
    
- **LGBMC Classifier:**
    - Training Accuracy: 0.9085
    - Testing Accuracy:  0.804
   

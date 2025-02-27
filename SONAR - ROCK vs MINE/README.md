## SONAR detection - ROCK vs MINE

This is a simple Logistic Regression model which predicts whether an object detected by the SONAR is a ROCK or a MINE.

### Steps to run the model
1. Copy the **prediction_model_sonar** file to your local project directory
2. install pickle and open the model

```
    import pickle
    with open('prediction_model_sonar','rb) as f:
        model = pickle.load(f)
    
    model.predict(input_data)
```

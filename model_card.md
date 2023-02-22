# Model Card


## Model Details

The model is XGBOOST classifier

## What this predicts

Based on Census data like Age, Occupation, education this predicts whether income exceeds $50K/yr based on census data.

## Training Data

We have used the training data (https://archive.ics.uci.edu/ml/datasets/census+income)

## Validation Data

We have used 20% data for validation

## Accuracy Metrics

The model was evaluated on: Precision,Recall and Fbeta.
Precision:  0.61. Recall:  0.39. Fbeta:  0.48


## Ethical Considerations

Given that the data contains personal attributes about gender, race and so on, special consideration should be given to how the model
performs on different groups.

## Caveats and Recommendations

To further improve the performance, we can  optimize hyperparameter. Currenty my model seems to be underfit which we can optimize with more data. For now I have only considered a small set of data.

## Stack Overflow Multilabel Tag Prediction

This project builds a multilabel classification model using a BiLSTM to predict the top 10 Stack Overflow tags for each question.

### Files
- `stackoverflow.ipynb`: Main notebook with training and evaluation
- `bilstm_stackoverflow_with_answers.h5`: Trained model weights

### Instructions
Follow the notebook to understand data cleaning, model building, training, and predictions.

### Output File (Not Uploaded)
Output file `top10_stackoverflow_predictions.csv` (~ 2 GB) is **not uploaded** due to GitHub’s file size limits.

You can regenerate it by running the last cell in the notebook:

```python
questions[["Id", "text", "Predicted Tags"]].to_csv("top10_stackoverflow_predictions.csv", index=False)
```

### Author
Parmeet Singh Majethiya

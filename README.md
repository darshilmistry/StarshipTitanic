# Spaceship Titanic

## Version 1

Converted all the columns into binary ones except the age and the the passenger id.

Using that approach, I got an **accuracy of 0.74**.

## Version 2

Reverted the services usage back to the original form, and surprisingly improved the **accuracy to 0.80** after Hyperparameter tuning.

# Model Accuracy

### Classification Report

|              | precision | recall | f1-score | support |
| ------------ | :-------: | :----: | :------: | :-----: |
| False        |   0.76    |  0.82  |   0.79   |   612   |
| True         |   0.83    |  0.78  |   0.80   |   692   |
|              |           |        |          |         |
| accuracy     |           |        |   0.80   |         |
| macro avg    |   0.80    |  0.80  |   0.80   |  1304   |
| weighted avg |   0.80    |  0.80  |   0.80   |  1304   |

### Confusion Matrix

|       | Positive | Negative |
| ----- | :------: | :------: |
| True  |   499    |   113    |
| False |   154    |   538    |

### Kaggle

**Rank :** 1052 (Last Checked 2024-06-24 18:51:08) \
**Accuracy :** 0.79705

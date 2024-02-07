# beat_check
#### About:
A Deep Convolutional Neural Network that helps classify heartbeats from the given ECG images. The model aims to classify the five types of non-life-threatening arrhythmias and thus help enable hospitals to diagnose them efficiently.

Classes: ['N': 0, 'S': 1, 'V': 2, 'F': 3, 'Q': 4]
- N : Non-ecotic beats (normal beat) 
- S : Supraventricular ectopic beats 
- V : Ventricular ectopic beats 
- F : Fusion Beats 
- Q : Unknown Beats

#### Dataset: https://www.kaggle.com/code/gregoiredc/arrhythmia-on-ecg-classification-using-cnn/input

#### Paper referred: https://www.sciencedirect.com/science/article/abs/pii/S0010482517302810

#### Nuances:
- Performed EDA.
- Used SMOTE to augment data to better deal with the imbalanced data.
- Used Random Forest Classifier as well. 
- Used a custom CNN model based on the paper. 

#### Results:
The CNN showed a better performance for a maximum number of trial runs.

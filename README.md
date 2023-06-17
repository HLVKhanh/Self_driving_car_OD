Mental Disorders Classification Project

Goal: to classify between 3 disorders (schizophrenia, bipolar disorder, and depression) based on EEG signals.

Workflow: Firstly, the data is up-sampled by SMOTE to produce balanced data. Then, feature extraction and selection are used to reduce the number of irrelevant features. The final stage is a classification complied with machine learning and deep learning. 

Usage: 

  Data: catogircal_data_fillna.csv.
  
  topographic_map.ipynb: to plot topographic map based on PSD values on each EEG channel.
  
  Handle_imbalance_in_SZ_D_BD.ipynb: to handel imbalanced data with three methods (downsampling, upsampling by copying or SMOTE).
  
  Train_with_SMOTE.ipynb: to train and fine tune ML pipeline. 
  
  DL__Wrapped_into_sklearn.ipynb: to train and fine tune Neural Network classifier.

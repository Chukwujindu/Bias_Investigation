Machine learning algorithms like Support Vector Machines (SVM) have shown effective outcomes in healthcare 
through their assistance in the diagnosis and prediction of different medical challenges. Nevertheless, the possibility that 
these algorithms could introduce prejudices and discrimination in the healthcare industry particularly against underrepresented 
groups across protected characteristics is of great concern. This experiment is aimed at identifying the presence of bias in an 
SVM model used for predicting the presence of heart disease in a patient. 
We investigated whether there is gender discrimination and its influence on the accuracy of the predictions and if this 
influence could be considered as bias against either gender. 
The dataset for our experiment was obtained from Kaggle: https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction 
An SVM model was created, analysed and furthermore, the data was separated into male and female, retrained after which bias 
criteria were applied to analyse the model. The findings suggest that there could be bias in the SVM model used for predicting 
heart disease with higher accuracy for female than for male which suggest that the model performs better for female which could 
lead to incorrect predictions of heart disease mostly for male patients and by inference, the model exhibits some bias towards 
male individuals in terms of demographic parity. The implications of our study highlight the importance of ensuring that machine 
learning algorithms in healthcare should be fair and equitable for all patients across all protected.

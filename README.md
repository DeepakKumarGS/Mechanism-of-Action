##Repository for Mechanism of Action Prediction Competition in Kaggle

* Metric : Mean columnwise log loss
* Submission scored 3350 out of 4373 participants (Top 75 %).Private Score 0.01909
*Final Submission Model :
2 Layer neural network with batchnormalization and dropout.
Multilabel stratified Kfold cross validation n_folds=5
one hot encoded cp_time,cp_type and cp_dose.Removed cp_type='crl_vehicle' since they dont have any MoA's(targets).
Pytorch framework.

All the experiments are documented in exp.xlsx file , notebooks are available in notebook folder.

Link to competition:https://www.kaggle.com/c/lish-moa/data

# Machine-Learning-for-Breast-Cancer-Diagnosis

The goal of this project is to utilize machine learning for the classification stage – predict whether a candidate tumor region from the x-ray is malignant or benign. For this purpose, the dataset used consists of x-ray images from patients from both categories of tumor, i.e. posed as a binary classification task. Note that, the ROI definition and feature extraction stages were carried out a priori using standard tools, and this project will build a predictive modeling solution for diagnosis based on the features.  
  
  
The data is first preprocessed and split into train/test sets. Different classifier models are fit, along with hyper-parameter tuning, to evaluate their effectiveness on imbalanced datasets. In order to achieve variance reduction, an ensemble classifier is designed, wherein the best performing classifiers from the previous step are used as the base model. Resampling techniques are used to deal with the dataset imbalance and classifier models are rebuilt to understand their robustness. Finally, a Super Ensemble is built by designing a strategy to combine different sophisticated models from the previous steps. The designed models are evaluated using metrics such as precision/recall, specificity, F1 score, Geometric mean, and response receiver operating curves (ROC).  

## Results

![Alt text](./results.png?raw=true "Title")  
  
  
### Dataset 
The dataset can be downloaded from -
http://www.kdd.org/cupfiles/KDDCupData/2008/training_data.zip

### Requirements
The following need to be installed -  
pydotplus (pip install)  
imblearn (https://pypi.org/project/imbalanced-learn/)  




## Pulsar Stars classification - Model comparison
HTRU2 is a data set which describes a sample of pulsar candidates collected during the High Time Resolution Universe Survey .

Pulsars are a rare type of Neutron star that produce radio emission detectable here on Earth. They are of considerable scientific interest as probes of space-time, 
the inter-stellar medium, and states of matter.

As pulsars rotate, their emission beam sweeps across the sky, and when this crosses our line of sight, produces a detectable pattern of broadband radio emission. 
As pulsars rotate rapidly, this pattern repeats periodically. Thus pulsar search involves looking for periodic radio signals with large radio telescopes.

The purpose of this project is to implement a machine learning model that can predict the target class of each pulsar star record.

### About the dataset
The data set shared here was downloaded from Kaggle and it contains 16,259 spurious examples caused by RFI/noise, and 1,639 real pulsar examples. 
These examples have all been checked by human annotators.

Each row lists the variables first, and the class label is the final entry. The class labels used are 0 (negative) and 1 (positive).

### Kernel content
1. Load and perform basic data cleaning
2. Exploratory data analysis with visualizations 
3. Class imbalance with SMOTE
4. Implement models
  * Decision tree
  * Naive Bayes
  * KNN
  * SVM

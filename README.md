# Toxicity
 The dataset includes 171 molecules designed for functional domains of a core clock protein, CRY1, responsible for generating circadian rhythm. 56 of the molecules are toxic and the rest are non-toxic.

### <span style="color:#FFFF00"> Information: </span>
| Dataset Characteristics | Subject Area | Associated Tasks | Attribute Type | Instances | Attributes |
|---------|:-------------|:--------------:|:-------------|:-------------|--------------:|
| Tabular | Life Sciences | Classification | - | 171 | 1203 |

<b>What do the instances in this dataset represent?</b>

Small molecules

<b>Was there any data preprocessing performed?</b>

The data consists a complete set of 1203 molecular descriptors and needs feature selection before classification since some of the features are redundant. We used Recursive Feature Elimination together with Decision Tree Classifier (DTC) to get the best set of molecular descriptors for DTC. Subsetted data with 13 features is included as supplementary file.

### <span style="color:#FFFF00"> Task: </span>

Implement an SVM algorithm using any benchmark data of your choosing; the only condition for the data is that it must have 1000 columns (features) or more,   then use Genetic Algorithm (GA) to implement dimensionality reduction be feature selections.

### <span style="color:#FFFF00"> Conclusion: </span>

The SVM algorithm is a powerful technique for classification problems, but its performance can be improved by selecting a relevant subset of features.

In this study, we performed an exploratory data analysis and found that the dataset consisted of 1003 continuous and 200 discrete features with no missing values or redundant instances. We implemented an SVM algorithm using Python's scikit-learn library and used GA for feature selection. The accuracy of the SVM model improved from 54.3% before feature selection to 68.6% after feature selection. This indicates that GA was able to identify a subset of features that significantly improved the performance of the model.

In summary, the combination of SVM and GA is an effective approach for solving classification problems that involve large and complex datasets. The results of this study demonstrate the importance of feature selection in improving the accuracy of SVM models and highlight the potential of GA as a powerful feature selection technique.

### References:

UC Irvine Machine Learning Repository. (n.d.). UC Irvine Machine Learning Repository. [https://archive-beta.ics.uci.edu/dataset/728/toxicity-2](https://archive-beta.ics.uci.edu/dataset/728/toxicity-2)

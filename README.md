# US-Election-Analysis-2016

##### Contributers:
- Andy Tran
- Lilian Li

### Predictive Algorithms
- **Random Forest**
- **Support Vector Machines**
- **Hierarchel Clustering**
- **Principle Component Analysis**
- **Decision Trees**
- **Lasso Regression**
- **Quadratic Discriminant Analysis**

## Conclusion
We performed hierarchical clustering with complete linkage on two sets of data; original and the same set of data that has been through principal component analysis. From that we concluded the PCA data displayed better clustering. By applying principal component analysis before clustering improves noise reduction and eliminates low variance dimension. By dimension reduction, PCA also sets everything into the same scale and also reduces number of features but emphasizes variance, and reduction of mean squared error.

Random forest performed the best out of all our classifiers. Random forests by fitting a number of a decision tree classifiers on subsamples we saw a great improvement of test accuracy. The model had a 95% accuracy rate when tested on our test set. For comparison our next best classifier was the decision tree classifier which had a 93% accuracy rate. However, our QDA classifier did the worst among all models, this maybe because in this model it might've been too flexible, thus a greater misclassification rate. All in all, with our best predictive model we were able to classify 95% the states correctly.

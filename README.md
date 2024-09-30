# Problem statement
Machines are critical to all businesses nowadays, and we expect them to operate at peak levels for a long time. Normally, we can use corrective maintenance strategies to make the best use of machines. However, we could end up incurring even higher costs due to downtime and labor.

Preventive maintenance comes in to reduce unplanned failures while businesses try to address problems in advance. However, the costs could still be high. By using predictive maintenance, we can prevent those unexpected problems more efficiently. We can fix the machines just in time as we monitor and predict the status of them.

In this project, predictive maintenance is the main concept. There are two aspects to the predictive maintenance in this project, supervised and unsupervised learning. In supervised learning, predicting remaining useful life and failure prediction are the goals. While in unsupervised learning, detecting anomalies of the machine is the target. Python and its machine learning-related libraries are the main tools in this project. The solution of this project could help the industry to lower the chance of unexpected downtime and reduce costs.

# Aims and objectives
The aim of this project is to propose machine learning solutions for predictive maintenance in response to Industry 4.0. There are three tasks proposed:
* Anomaly detection: The model should be able to detect the anomalies within data.
* Remaining useful life prediction: The model should be able to predict the remaining useful life of a machine to help people be prepared for maintenance or replacement.
* Failure prediction: The model should be able to predict whether there will be a failure.

# Data source
There are two datasets used in this project as you can find in the Datasets folder:

# Solution approach
This project follows the CRISP-DM methodology. Supervised and unsupervised algorithms are used to address set tasks. Please notice that an artificial neuron network (ANN) is not explored in this project.
* Anomaly detection: Local Outlier Factor (LOF), Elliptic Envelope, Isolation Forest, and One-Class Support Vector Machine (SVM) are used.
* Remaining useful life prediction: Support Vector Machine Regressor is used. For automated machine learning examples, a Tree-based Pipeline Optimization Tool (TPOT) is used. The output best model is evaluated together. Since the data is rather high-dimensional, feature importance analysis is performed to reduce the training size. The feature-reduced version of the dataset is also modeled to compare the computing time and results.
* Failure prediction: Logistic Regression, KNeighbors Classifier, C-Support Vector Clas- densification with liner kernel, C-Support Vector Classification with RBF kernel, Gaussian Naive Bayes, Decision Tree and Random Forest Classifier are applied.

# Summary of contributions and achievements
* Anomaly detection: All the models achieved almost a 100% recall rate and over 70 F1 score.
* Remaining useful life prediction: The remaining useful life of the battery can be predicted with errors of around 2 cycles. 
* Failure prediction: The best classifier achieves 87.51% accuracy and five classifiers achieve over 80% accuracy. You can find the results in 

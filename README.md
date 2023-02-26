# Deep-Transfer-Learning-Techniques-Based-Automated-Classification-and-Detection-of-Pulmonary-Fibrosis
Deep Transfer Learning Techniques-Based Automated Classification and Detection of Pulmonary Fibrosis from Chest CT Images
Abstract
Pulmonary Fibrosis (PF) is a non-curable chronic lung disease. Therefore, a quick and accurate PF diagnosis is imperative. In the present study, we aim to compare the performance of the six state-of-the-art Deep Transfer Learning techniques to classify patients accurately and perform abnormality localization in Computer Tomography (CT) scan images. A total of 2299 samples comprising normal and PF-positive CT images were preprocessed. The preprocessed images were split into training (75%), validation (15%), and test data (10%). These transfer learning models were trained and validated by optimizing the hyperparameters, such as the learning rate and the number of epochs. The optimized architectures have been evaluated with different performance metrics to demonstrate the consistency of the optimized model. At epoch 26, using an optimized learning rate of 0.0000625, the ResNet50v2 model achieved the highest training and validation accuracy (training = 99.92%, validation = 99.22%) and minimum loss (training = 0.00428, validation = 0.00683) for CT images. The experimental evaluation on the independent testing data confirms that optimized ResNet50v2 outperformed every other optimized architecture under consideration achieving a perfect score of 1.0 in each of the standard performance measures such as accuracy, precision, recall, F1-score, Mathew Correlation Coefficient (MCC), Area under the Receiver Operating Characteristic (ROC-AUC) curve, and the Area under the Precision recall (AUC_PR) curve. Therefore, we can propose that the optimized ResNet50v2 is a reliable diagnostic model for automatically classifying PF-positive patients using chest CT images.
Keywords: pulmonary fibrosis; transfer learning techniques; ResNet50v2; chest computed tomography; classification and detection
### Screenshot
###### Home page
![](/images/HomePage.jpg)
######Upload Page
![](/images/UploadFibronosis.jpg)
###### Prediction page
![](/Result/4.JPG)
# Flow Diagram
![](/images/FlowDigram.jpg)
# Operational Diagram
![](/images/OpratinalFlowDiagram.jpg)
# Augmentation
![](/images/AugRVFinal.jpg)
# Requirements
Werkzeug>=2.2.2
Flask-Cors==3.0.10
Flask>=2.2.2
numpy==1.20
Keras==2.9.0
pillow>=9.3.0
h5py==3.7.0
tensorflow>=2.9.1
gunicorn>=19.5.0
# Application
<a href="https://fibrosisweb.azurewebsites.net/">https://fibrosisweb.azurewebsites.net/</a>
<br/>
# How to cite ?
Syed, A.H.; Khan, T.; Khan, S.A. Deep Transfer Learning Techniques-Based Automated Classification and Detection of Pulmonary Fibrosis from Chest CT Images. Processes 2023, 11, 443. https://doi.org/10.3390/pr11020443

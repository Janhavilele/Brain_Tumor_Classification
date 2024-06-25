# Brain_Tumor_Classification

Created a model that can correctly classify the tumor type using hybrid model.

_**Steps:**__

**1) Data Collection:**
- https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri dataset is used.
- In this dataset four types of tumor present - Glioma tumor , Pitutory tumor , Meningioma tumor , No tumor which is divided into training and testing part.

**2) Data Preprocessing:**
- First check the dataset is balanced or not. Remove noise from the dataset.
- Images are imported from training and testing directories,resize it and appended to x_train and corresponding labels to y_train.
- Data is converted into numpy array.
- Sample image is displayed using matplotlib and in RGB format.

**3) Model training :**
- Model is trained on 3 ML algorithms(SVM,Logistic regression,Random forest)
- Random forest give greater accuracy so for machine learning random forest were selected.
- For deep learning Effnet were used because it is used for large scale dataset.

**4) Model Evaluation :**
- It is done using Precision,Recall and Accuaracy.

**5) Model Comparison:**
-Created a model with Machine learning,Deep learning separately and then combined them(hybrid) and check the accuracy.


_ **Result and conclusion :**_

1) Random forest -> 84.41% accuracy
2) Effnet -> 97.04% accuracy
3) Random Forest + Effnet (Hybrid) -> 98.67% accuracy.

**From the result obtained project conclude that combination of machine learning and deep learning gives better accuracy.**

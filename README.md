# Chest_Xray
Predicting pneumonia with chest xray scans
In this kernels competition we are given the data of chest x-rays for training and validation
Using a simple CNN model with data augmentation we get an accuracy of 92% on the trianing set and almost 86% on the testing dataset.
Keras has been used to make the CNN model
and results of the model loss and accuracy are plotted

Dataset Info
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

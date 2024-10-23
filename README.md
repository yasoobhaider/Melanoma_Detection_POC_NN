# Melanoma_Detection_POC_NN
This is POC completed for detecting melanoma in patients with images of their skin lesions and pigmentation
**Table of Contents**
General Info
Technologies Used
Conclusions
**General Information**
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. In this assignment, I am building multiclass classification model using a custom convolutional neural network in TensorFlow. The model can classify images in malignant and benign oncological diseases (Actinic keratosis,Basal cell carcinoma,Dermatofibroma,Melanoma,Nevus,Pigmented benign keratosis,Seborrheic keratosis,Squamous cell carcinoma,Vascular lesion)
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
**Technologies Used**
Tensorflow - version 2.8.0
Numpy - version 1.19.5
Pandas - version 1.1.5
Matplotlib - version 3.2.2
Scikit-learn - version 1.0.2
Augmentor - version 0.2.10
PIL - version 7.1.2
Contact
Created by [@UpgradGhuleSiddharth] - feel free to contact me!
**Conclusions**
Image augmentation got rid of overfitting
Rectifying the class imbalance got rid of underfitting
Need to alter the learning rate of the model to improve overall accuracy or add some more layers

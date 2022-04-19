# Melanoma Detection


In this assignment, you will build a multiclass classification model using a custom ___convolutional neural network in tensorflow.___     

___Problem statement:___ To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.   

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. 

The data set contains the following diseases:  
- Actinic keratosis 
- Basal cell carcinoma 
- Dermatofibroma 
- Melanoma 
- Nevus 
- Pigmented benign keratosis 
- Seborrheic keratosis 
- Squamous cell carcinoma 
- Vascular lesion

The following steps are done while building the different models:
- Data Reading/Data Understanding 
- Dataset Creation and visualisation
- Model Building & training (Base Model)
- Data augmentation strategy to resolve underfitting/overfitting 
- Model Building & training on the augmented data
- Class distribution Examination
- Handling class imbalances
- Model Building & training on the rectified class imbalance data :

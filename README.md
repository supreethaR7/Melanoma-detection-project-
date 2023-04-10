# Melanoma-detection-using-CNN in Tensorflow

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

a. Actinic keratosis
b. Basal cell carcinoma
c. Dermatofibroma
d. Melanoma
e. Nevus
f. Pigmented benign keratosis
g. Seborrheic keratosis
h. Squamous cell carcinoma
i. Vascular lesion

Project Pipeline


a. Data Reading/Data Understanding: Defining the path for train and test images

b. Dataset Creation: Create train and validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.

c. Dataset visualisation: Create a code to visualize one instance of all the nine classes present in the dataset

d. Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

e. Choose an appropriate optimiser and loss function for model training

f. Train the model for ~20 epochs

g. Write your findings after the model fit, see if there is evidence of model overfit or underfit

h. Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data :

i. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

j. Choose an appropriate optimiser and loss function for model training

k. Train the model for ~20 epochs

l. Write your findings after the model fit, see if the earlier issue is resolved or not? **Class distribution: **

m. Examine the current class distribution in the training dataset

n. Which class has the least number of samples?

o. Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances:

p. Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data:

q. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

r. Choose an appropriate optimiser and loss function for model training

s. Train the model for ~30 epochs

t. Write your findings after the model fit, see if the issues are resolved or not?

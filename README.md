# Detection of Melanoma using CNN
> To build a CNN based model which can accurately detect melanoma.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- The aim of this project is to detect melanoma - a type of cancer using CNN
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
  - The data set contains the following diseases:
    1. Actinic keratosis
    2. Basal cell carcinoma
    3. Dermatofibroma
    4. Melanoma
    5. Nevus
    6. Pigmented benign keratosis
    7. Seborrheic keratosis
    8. Squamous cell carcinoma
    9. Vascular lesion

## Technologies Used
- TensorFlow - 2.13.0
- numpy - 1.23.5
- keras - 2.13.1
- pathlib - 1.0.1
- pandas - 1.5.3
- matplotlib - 3.7.1

## Conclusions
- Without the usage of batch normalization overfitting of model was observed. The validation accuracy didn't improve beyond 57%
- With the usage of dropout and batch normalization the overfitting was controlled
- The final model had the overall accuracy of 90.54% and validation accuracy of 85.97%
- However, the overall testing accuracy was only 35%
- With the changes in hyperparameters the accuracy can be improved further

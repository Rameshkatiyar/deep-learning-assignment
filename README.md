# Detect Melanoma
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

1. Basal cell carcinoma
2. Dermatofibroma
3. Melanoma
4. Nevus
5. Pigmented benign keratosis
6. Seborrheic keratosis
7. Squamous cell carcinoma
8. Vascular lesion


## Conclusions
- Training accuracy = ~88%.
- Validation accuracy = ~78%.
- Though the model accuracy has improved, the class rebalance has helped treat the overfitting to some extent.
- Much better models could be built or tried out using more epochs and more layers.


## Technologies Used
- pandas
- numpy
- matplotlib
- tensorflow
- glob


## Contact
Created by [@Rameshkatiyar] - feel free to contact me!
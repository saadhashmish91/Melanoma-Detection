# Project Name
> Melanoma Detection using CNN

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the business probem that your project is trying to solve?

- What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions
- Initial tests were showing high training accuracy and lower validation accuracy, pointing towards overfitting
- Overfitting was resolved by using augmentation strategies (flipping, rotation, zoom, etc.). Also drop out layers are used to address the issue
- Class imbalance was predominant here. We needed to add some additional images (500) to each class to reduce the imbalance. The whole process is repeated post that
- Once data augmentation is done by removing imbalance, the accuracy improves significantly to over 80%


## Contact
Created by [@saadhashmish91] - feel free to contact me!

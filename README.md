# Melanoma Detection
The objective of this project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. 
- The data set contains the following diseases:

  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- we found that the accuracy on both the training and validation data has increased after solving class imbalance problem and using Data augmentation. The training accuracy is 90.11% and validation accuracy is 83.89% which shows we finally able to tackle the problem of overfitting that we were facing during initial stages. Similarly both the training and validation loss droped to much extent.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy library - version 1.21.6
- pandas library - version 1.3.5
- matplotlib library - version 3.5.1
- tensorflow library - version 2.11.0
- Augmentor library - version 0.2.10

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
### References
- https://www.tensorflow.org/api_docs/python/tf/all_symbolshttps://www.tensorflow.org/api_docs/python/tf/all_symbols
- https://keras.io/api/
- https://towardsdatascience.com/
- https://www.geeksforgeeks.org/



## Contact
Created by [@swarajoneil] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

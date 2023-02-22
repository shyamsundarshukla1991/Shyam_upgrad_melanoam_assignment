# Project Name
<!-- > Outline a brief description of your project.-->
I will build a multiclass classification model using a custom convolutional neural network in TensorFlow(keras) for melanoma detection from images. 



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  - To build a multiclass classification model using a custom convolutional neural network in TensorFlow(keras) for melanoma detection from images. 
- What is the background of your project?
  - Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the business probem that your project is trying to solve?
  - To build a CNN based model which can accurately detect melanoma. 
- What is the dataset that is being used?
  - The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- There is a class imbalance in the dataset with certain classes dominating over others
  - actinic keratosis-114 samples
  - basal cell carcinoma - 376 samples
  - dermatofibroma -  - 95 samples
  - melanoma - 438 samples 
  - nevus - 357 samples 
  - pigmented benign keratosis - 462 samples 
  - seborrheic keratosis - 77 samples 
  - squamous cell carcinoma - 181 samples 
  - vascular lesion - 139 samples
- Without Batch Normalisation and dropout the model overfits and the accuracy is also low
- With Batch Normalisation and dropout the accuracy improves, the model becomes more stable
![image](https://user-images.githubusercontent.com/111374919/220699820-46e47c3f-3de3-44b9-b4ef-8c25b0c3baf6.png)


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - version 2.11.0
- Keras - version 2.11.0
- numpy - version 1.23.2
- pandas - version 1.4.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
  - https://www.tensorflow.org/api_docs/python/tf
  - keras.com
- This project was based on assignment in upgrad course [this Course](https://www.upgrad.com).


## Contact
Created by [@shyamsundarshukla1991] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

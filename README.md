# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- The dataset used consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
A CNN model is built for classification of skin diseases into 9 different classes.

While training the model, various strategies like data augmentation, handling class distribution issues are implemented to avoid over fitting and class imbalance.

Model parameters:
- Input layer
- 4 convolution layers
- 3 pooling layers with max pooling
- 1 FC layer
- Output layer with softmax
- Dropout of 0.1 after each pooling layer
- Trained the model for 50 epochs


The model with above parameters had given 82.7% training accuracy and 81.8% test accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3
- Matplotlib - version 3.7.0
- Pandas 	 - version 1.5.3
- Numpy  	 - version 1.23.5
- Seaborn 	 - version 0.12.2
- SKLearn    - version 1.2.2
- TensorFlow - version 2.15
- Keras      - version 2.15

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is solely contributed by the below author.
 [@kiranp37](https://github.com/kiranp37/)


## Contact
Created by  [@kiranp37](https://github.com/kiranp37/) - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
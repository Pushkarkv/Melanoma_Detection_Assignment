# Project Name
> Image Classification model to predict the different categories of skin cancers.


## Table of Contents
* [General Info](#general-information)
* [Libraies Used](#Libraies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- The data set contains the following diseases:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Initially we used a normal CNN network and we got very high train accuracy with very bad validation accuracy. Clearly indicating overfitting.
- Then we added data augmentation and introduced dropots and improved the validation accuracy by 5%. The train accuracy also came very close making the model generalize better.
- We then checked the no of images of each class and found out that seborrheic keratosis was the least popular with 77 samples while pigmented benign keratosis was most repeated with 462 samples.
- We finally used Augmentor library to increase the examples of each class by 500 making the data balanced. We finally got very good train accuracy of 82% and validation accuracy of 78%.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Libraies Used
- pathlib==1.0.1
- tensorflow==2.12.0
- matplotlib==3.7.1
- numpy==1.23.5
- pandas==1.5.3
- google==2.0.3
- Augmentor==0.2.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@Pushkarkv] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
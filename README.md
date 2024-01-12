# Age-and-Sex-Prediction
# DL Simplified
Deep Learning has many application in the field of computer vision and one such application is Facial Detection & Recognition in which we also coined the work for age and sex detection 

## ✨Age and Sex Detection✨

### Aim 
The objective of the project is to Create a DL based model which can detect gender and age using facial images. Convolutional Neural Network is used to classify the images. There are 2 output types namely, gender(M or F) and age.

### Datasets
I have used Kaggle's  [UTKFace](https://www.kaggle.com/datasets/jangedoo/utkface-new) dataset. 

##### About Dataset
The dataset consists of over 20,000 face images with annotations of age, gender, and ethnicity. The dataset is a large-scale face dataset with long age span (range from 0 to 116 years old). Images cover large variation in pose, facial expression, illumination, occlusion, resolution, etc. Dataset could be used on a variety of tasks, e.g., face detection, age estimation, age progression/regression, landmark localization, etc.

dataset image sample - 

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/b2e5e829df2986d9da073a6bc5493a60bcdf916d/Images/OneoftheDatasetImage.png)

### Approach
In the notebook we have trained an pretrained CNN model using the above dataset  and adjusting the algorithm. It also uses Convolutional Layers from Convolutional Neural Networks and compare the accuracy for age and gender and it also figure out the loss during model training. We have trained the model with large variation of images which covers pose, facial expression, illumination,  occlusion, resolution, etc so that we can enhance the accuracy of the model.


Model Used 

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/ModelUsed.png)


### Output

- Frequency Distribution of age of images used in dataset.

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/AgeDistribution.png)

- Grid View of few Images used in Dataset 

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/DatasetPlot.png)

- Gender Distribution 

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/GenderDistribution.png)


- Accuracy and Loss Graph for Gender 
Accuracy

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/AccuracyforGender.png)

Loss 

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/genderloss.png)

- Accuracy and Loss Graph for Age

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/Age.png)



## Testing 
Testing on random image from index 1-23708, you can also test by changing index of the image used for test, variable name image_index.

- Test Image 

Original Gender: Male Original Age: 10

Predicted Gender: Male Predicted Age: 11

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/test1.png)


- Test Image 

Original Gender: Male Original Age: 25

Predicted Gender: Male Predicted Age: 24

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/test2.png)



- Test Image 

Original Gender: Female Original Age: 29

Predicted Gender: Female Predicted Age: 29

![image](https://github.com/EshanRS/Gender-and-Age-Prediction/blob/cdc5c78f196ee741dfd70a88d19983ad89863bab/Images/test3.png)




## Conclusion
We can vary the number of epochs to get more accuracy on models, here we have achieved the accuracy of more than 95% 


## License
MIT

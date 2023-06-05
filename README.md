# Pneumonia_chestx-ray
A dramatic increase in the number of suspected cases of Pneumonia over the past few years has
contributed to the collapse of many health systems over the world. This has led to the need to
find an efficient, quick, and accurate method to alleviate the overburdening of radiologists&#39;
efforts to diagnose suspected cases, which has emerged as an issue in this area. It is an infection
that causes inflammation of the lungs and can be fatal if not caught and treated by a doctor in a
timely manner. A chest X-ray is commonly used to detect pneumonia, but it is imperative to
remember that an expert examination of chest X-ray images is required for the successful
diagnosis of pneumonia. Detecting pneumonia using chest X-ray images by an expert can be
time-consuming and inaccurate because of the time-consuming process involved. A customized
version of Resnet 50 was proposed in this research as a way of extracting characteristics from
chest X-ray images and classifying them to detect whether a person has pneumonia or not. I have
collected a dataset from Kaggle. The data set contains two folders: training and testing. During
pre-processing, I have done data balancing and afterwards, I have split the training data into two
parts, one for training and one for validation. To enhance the model performance, I have added
data augmentation to increase the amount of variation in images, and I have also created data
generators to overcome memory issues while training the model. The custom Resnet 50
architecture has been built from the ground up and trained with training data and I used the
validation data for validation purposes.

Dataset link: https://www.kaggle.com/datasets/tolgadincer/labeled-chest-xray-images.

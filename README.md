# smartathon
a dataset of images that I will use to train a machine learning model to detect various objects and classify them as different types of visual pollution. Here is an example of with loading the dataset, training a model, and making predictions on the test set.



Visual Pollution Detection. 

Since visual pollution is a relatively recent issue compared to other forms of environmental contamination, study is needed to define, formalize, measure, and evaluate it from many angles. This competition aims to establish a new field of automated visual pollution classification, utilizing the technological prowess of the twenty-first century for environmental management applications. By training and testing approaches to convolutional neural networks we expect competitors to simulate the human learning experience in the context of picture identification for the classification of visual pollutants. Additionally this will be useful for the development of a "visual pollution score/index" for urban areas that might produce a new "metric" or "indicator" in the discipline of urban environmental management. In this competition, you will build and optimize algorithms based on a large-scale dataset. This dataset features the raw sensor camera inputs as perceived by a fleet of multiple vehicles in a restricted geographic area in KSA If successful, you’ll make a significant contribution towards stimulating further development city planning and empowering communities around the world

Task:
You are required to build a machine learning model that can detect various objects in images.

The dataset folder contains the following files: 
Images (folder): It contains 9966 
test.csv 2092 × 1 
train.csv: 19950 × 7 

The columns provided in the dataset are as follows:
Class: Represents the class of object detected (float)
Image_path: Represents the image name (string)
Name: Represents the name of object detected (string)
Xmax: Represents the xmax coordinate of bounding box (float)
Xmin: Represents the xmin coordinate of bounding box (float)
Ymax: Represents the ymax coordinate of bounding box (float)
Ymin: Represents the ymin coordinate of bounding box (float)

Read the test.csv file into a numpy array, and then generate predictions
Save the predictions to a file that you will email with your code

Give me code for test and Save the predictions to a file
Note Result submission guidelines:
The submission file must be submitted in .csv format only.
The submission file must be contain prediction for all 2092 images.
Note : Ensure that your submission file contains the following:
Correct image_path values as per the test file
Correct names of columns like this following
class	image_path	name	xmax	xmin	ymax	ymin

![image](https://user-images.githubusercontent.com/80965738/213448676-0af96de7-ceab-4492-9ced-92b1ad2a4f7f.png)

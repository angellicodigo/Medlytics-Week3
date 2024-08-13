# Medlytics Week 3 Project

## Background
Image Analysis challenge by classifying mammogram images. Created by Thomas Possidente.

## Dataset
http://marathon.csee.usf.edu/Mammography/Database.html

## Presentation
Our team focused on preprocessing techniques to increase the dataset including contrast limited adaptive histogram equalization (CLAHE), rotations, and jitter. We found random forest being a reliable model for image classification. We plan to improve multi-class classification using larger deep learning models.

Here is a visual difference of CLAHE.

![Example of CLAHE with our data](https://github.com/angellicodigo/Medlytics-Week3/blob/main/Week-3-Team-4/CLAHE.png)

Here is a visaul difference of Jitter.

![Example of Jitter with our data](https://github.com/angellicodigo/Medlytics-Week3/blob/main/Week-3-Team-4/JITTER.png)

Here is a table of our results for each model. 

| Performance of CNN (Binary classes) | Performance of Random Forest (Binary classes) |
| --- | --- |
|  Test Accuracy: 0.685 | Test Accuracy: 0.849  |
| ROC Curve area under curve (AUC): 0.845 | ROC Curve area under curve (AUC): 0.806  |
|  Confusion Matrix Score: 421 | Confusion Matrix Score: 1600  |

| Performance of K-means (Multi-classes) | Performance of CNN (Multi-classes) |
| --- | --- |
|  Test Accuracy: 0.185 | Test Accuracy: 0.608  |
| ROC Curve area under curve (AUC): 0.491 | ROC Curve area under curve (AUC): 0.871  |
|  Confusion Matrix Score: -2476 | Confusion Matrix Score: 98  |

# What does Medlytics Week 3 contains?
Welcome! This is the repository for all lectures, assignments, and datasets for Week 3 of the BeaverWorks Medlytics course for 2022. The slides are provided here for easy reference, but will be presented in lecture format. You should fork this repository at the beginning of the week and work on your own copy when completing notebooks and challenge projects.

Datasets Used in this Repo:

CBIS-DDSM: https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM 
Jpegs and labels were extracted from a tfrecords dataset curated by Eric Scuccimarra: https://www.kaggle.com/skooch 
Colorectal Histology Dataset: https://zenodo.org/record/53169#.W2hf_NJKh9M 
Kather JN, Weis CA, Bianconi F, Melchers SM, Schad LR, Gaiser T, Marx A, Zollner F: Multi-class texture analysis in colorectal cancer histology (2016), Scientific Reports (in press)

## Notebooks
* Contains Jupyter Notebook lessons where students will need to write their own code
* Contains Jupyter Notebook Solutions (will be uploaded after lesson notebooks are completed by students)
* Contains lesson notebooks (and solutions) on Texture Classification, Classification with Convulutional Neural Nets, Classification with Neural Nets, Classification using ImageNet, and Classification using VGG16. All notebooks made by Siddharth Samsi.

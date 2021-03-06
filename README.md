# Retina Diseases Diagnosis : Using Deep Learning and Machine Learning Techniques

<!DOCTYPE html>
<html>
<head>

</head>
<body>

<h2>Feature Extraxction and Classification of Retina Diseases from OCT Images</h2>
  
<h3><b> Description of the project</b></h3>

<p>This project is about the classification of three Retina diseases
as CNV, DME and DRUSEN and Normal Retina from eye OCT images. 
The Dataset consists of three main folders as train, test and val, 
which each of them include four folders named CNV, DME, DRUSEN 
and NORMAL with Retina OCT images for each case. There are 7752 files
in train folder, 1000 files in test folder and 501 files in val folder
for validation. This Dataset is a subset of the Kermany OCT Dataset.</p>

<p> This project consistes of two main parts. The first one is to seek
which Machine Learning or Deep Learning Algorithm can extract the features
of different classes more effectively.The feature extraction techniques
include PCA, CNN, pre-trained VGG16 and ResNet50, ZFNet U-like architecture
and Random Forest was applied as the clasifier for all feature extraction methods.
The second part is to compare different classification techniques from
Deep Learning and Machine Learning. 
Deep Leaning techniques that applied was CNN, CNN with last layer
functining as SVM, Transfer Learning using VGG16 and ZFNet.
Random Forest Classifier is the Machine Learning technique
used for the classification. </p>

<p> The performance of feature extraction and classification comparisons
was evaluated using different metrics such as Sensitivity,
Precision, FNR, F1-socre, Accuracy and Cross-Validation.</p>

<p> The performance of different techniques were also comapred according 
to the time of training and the memory they occupied during training.</p>


<h2>Methodology</h2>


<img src="https://user-images.githubusercontent.com/42371862/163312391-02c56786-9d9c-4da4-a6c6-2643e89a5bf3.png" alt="Methodology" alt="Methodology" width="867" height="680">

</body>
</html>



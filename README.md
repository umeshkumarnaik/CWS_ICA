# Coursework


**Team Name**:
<your_team_name> XYZ

**Team Members**:
* <name_1><roll_no><branch><bachelors/masters/phd>
* <name_2><roll_no><branch><bachelors/masters/phd>

**Project Title**:
Handwritten Signature Analysis and Verification

**Objective**:
The objective of this project is to analyze and quantify the variability of handwritten signatures using signal processing techniques, with the aim of developing an automated signature verification system.

**Background**:
Handwritten signatures are a common method of verifying identity in various sectors such as banking, employment, and education. However, manual verification of signatures can be subjective and prone to errors, especially when signatures are complex or stylized. By analyzing the trajectory of handwritten signatures using signal processing methods, we can extract meaningful features and patterns that can aid in categorization and verification of signatures.

**Methodology**:
We will use a publicly available dataset of multi-script handwritten signatures to train and test our model. We will extract the signature trajectories from the signature image using image binarization and apply interpolation to smoothen noisy or broken parts. Then, using Fourier analysis, we will analyze the rate of variations and periodicities of the trajectories along each dimension as 1-D signals. Features quantifying these variations will be extracted and used to carry out unsupervised clustering using PCA and k-means to explore the possibility of categorizing signatures.

To develop a signature verification system, we will use the extracted features to train a machine learning model such as a logistic regression or a neural network. The performance of the model will be evaluated using metrics such as accuracy, precision, recall, and F1-score. We will compare the performance of our model with recent methods in the literature ([1,2]).

**Deliverables**:
* A .ipynb notebook detailing the variability analysis of handwritten signatures and the development of the signature verification system.
* A GitHub repository containing the source code and documentation of the project.
* An oral presentation in class.

**Dataset to be used**:
1. Multi-script handwritten signature (Roman and Devanagari) Dataset: It contains a total of 5433 signatures of 126 writers, out of which 3929 signatures are from 80 writers in Roman script and 1504 signatures are from 46 writers in Devanagari scripts. This dataset will be used for training and testing our model.
2. e-BioSign Database: The dataset comprises on-line signatures acquired from 5 different COTS devices in total, three Wacom devices (STU-500, STU-530 and DTU-1031) specifically designed to capture dynamic signatures and handwritng, and two Samsung general purpose tablets (Samsung Galaxy Note 10.1 and Samsung ATIV 7). For the two Samsung tablets, data is collected using both pen stylus and also the finger. Data was collected in two sessions for 65 subjects. Skilled forgeries were also performed. 

**References**:
1. Engin, D., Kantarci, A., Arslan, S., & Ekenel, H. K. (2020). Offline signature verification on real-world documents. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition workshops (pp. 808-809).
2. Kurowski, M., Sroczyński, A., Bogdanis, G., & Czyżewski, A. (2021). An automated method for biometric handwritten signature authentication employing neural networks. Electronics, 10(4), 456.

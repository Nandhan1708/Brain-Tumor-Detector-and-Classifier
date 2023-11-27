# Brain-Tumor-Detector-and-Classifier
Sensing the dire need of introduction of machine assisted testing in the 
field of medical science, our team has taken this task of detecting and classifying 
tumors based on societal concerns. The main idea behind brain tumor detection and 
classification using machine learning is to develop algorithms that can analyze 
medical imaging data, such as MRI or CT scans, to accurately identify and categorize 
brain tumors. Deep learning techniques can be applied to automate the process, 
assisting medical professionals in diagnosing and monitoring brain tumors. This 
field aims to improve the efficiency and accuracy of tumor detection, segmentation, 
and classification, leading to earlier detection, personalized treatment planning, and 
better patient outcomes. The project involves usage of VGG16, a CNN architecture developed by 
Visual Geometry Group in 2014. This deep neural network consists of 16 layers: 13 
convolution layers and 3 deeply connected layers, to achieve high accuracy for 
image recognition without compromising on the simplicity and uniformity the 
architecture provides. VGG16 has been given preference as it requires a lesser number of inputs to 
adapt and identify features, emphasizes on relative positioning of pixels and rectifies 
the shifts in the positions of pixels. Trained over ImageNet, an image dataset 
consisting of 1 million images within 1,000 categories, VGG16 has become a 
renowned name in the domain of Machine Learning.

# Challenges in the system
1. Limited and Imbalanced Data: Obtaining a large and well-curated 
dataset of brain tumor images can be challenging. The availability of 
labeled data is often limited, and there can be an imbalance in the 
number of samples across different tumor types, making it difficult to 
train accurate models.
2. Complex and Heterogeneous Tumor Patterns: Brain tumors can 
exhibit diverse characteristics and appearances, even within the same 
tumor type. Tumors can have variations in size, shape, location, and 
texture, making it challenging to capture all the variations and develop 
robust models that generalize well.
3. Generalization to New Data: It is essential for the models to 
generalize well to unseen data, especially when dealing with brain 
tumor detection and classification. The models should be able to 
accurately detect and classify tumors in images that are different from 
the training data, such as images from different institutions or with 
different imaging modalities.
4. Handling Small Tumors or Subtle Abnormalities: Detecting small 
tumors or subtle abnormalities in brain images can be challenging due 
to their low contrast and similarity to normal brain tissues. These 
abnormalities can be easily overlooked or misinterpreted, leading to 
false negatives or false positives.

# Dataset
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

# Plant-Disease-Detection-Using-Digital-Image-Processing
The plant disease detection system with efficient image segmentation and
 feature extraction algorithms and statistical models.

Abstract
One of the important and tedious task in agricultural practices is 
detection of disease on crops. It requires huge time as well as skilled labor.The system is 
able to detect 20 different diseases of 5 common plants with 93% accuracy.

Methodology
1) Dataset:The dataset consists of 87000 
RGB images of healthy and unhealthy plant leaves having 38 classes out of which We 
have selected only 25 classes for experimentation of our algorithm.

2) Data preprocessing and feature extraction: 

Original Image --> Grayscale Conversion --> Smoothening(Gaussian Filter) --> Otsu's Thresholding 
-->Morphological Transform(Shape Features)--> Bitwise AND Operation with original Frame
-->Gray level co-occurence matrix(Texture Features)

3)Classification Algorithm:
Random forest classifier has been used for classification or detection task.
Generally, to achieve higher accuracies, decision trees are used. But they are prone to 
overfitting problems. So to overcome this issue, random forest classifier is used which 
is a combination of multiple decision trees. 

4)Conclusion:
We have successfully developed a system for plant disease 
detection with average 93% accuracy and 0.93 F1 score. 
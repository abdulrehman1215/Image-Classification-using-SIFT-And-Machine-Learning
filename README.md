# Image-Classification-using-SIFT-And-Machine-Learning
## Link to datasets: 
1. Flowers DatSet: https://drive.google.com/drive/folders/1cZVW6fFzatJZ_h27BSn_sRwh3OATqPA-?usp=sharing
2. Objects Data Set: https://drive.google.com/drive/folders/1WiyRBgAT-RM9EHBne5Pv0iWI3oyq66oC?usp=sharing
# Abstract
Before deep learning, general machine learning algorithms combined with image processing techniques were used for computer vision tasks. This report presents a method for image classification using Scale-Invariant Feature Transform (SIFT) descriptors in combination with Random Forest and Support Vector Machine (SVM) classifiers. The proposed method involves extracting SIFT descriptors from images, building visual vocabulary using a clustering algorithm (K-Means in this case), and using them to train both classifiers. The Random Forest classifier and the SVM classifier are used to perform the actual classification. The method was tested on the objects dataset and flowers dataset and achieved accuracies of 1 and 0.57 respectively for Random Forest and 0.875 and 0.60 respectively for SVM. The results show that the proposed method can effectively classify images using SIFT descriptors in combination with machine learning classifiers. Further experiments can be conducted to explore the performance of other classifiers with SIFT descriptors and to optimize the parameters of the classifiers for better accuracy.
# Introduction
This assignment had two parts, i.e: Apply Image Classification using SIFT and Machine Learning algorithms such as SVM and Random forest classifier on:
1. Objects Data Set
2. Flowers Data Set
Image classification using basic machine learning models can be performed
in the following steps:
  1. Feature extraction: First, you need to extract features from each image in your dataset. The most common method is to use the Scale-Invariant Feature Transform (SIFT) algorithm to detect and describe key points in the image.
  2. Building a visual vocabulary: Once you have a set of feature descriptors for your images, you can build a visual vocabulary using clustering algorithms such as k-means. This step involves grouping similar descriptors together and selecting representative features (centroids) to build your vocabulary.
  3. Encoding images: After building the visual vocabulary, you can represent each image in your dataset as a histogram of visual word occurrences. This is done by assigning each feature descriptor in the image to the closest visual word in the vocabulary and incrementing the corresponding bin in the histogram.
  4. Training a classifier: With the encoded images, you can train a classifier using standard machine learning algorithms such as Support Vector Machines (SVM) or Random Forests. The classifier learns to predict the class labels of images based on their histogram of visual word occurrences.
  5. Testing the classifier: Finally, you can evaluate the performance of your classifier on a test set of images by computing metrics such as accuracy, precision, recall, confusion matrix, etc.

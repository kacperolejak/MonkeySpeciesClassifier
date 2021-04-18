## Final project for Machine Learning course at ii uwr (co-op with [Jakub Pacierpnik](https://github.com/qbencjusz))
Model to classify monkey species with images from [kaggle dataset](https://www.kaggle.com/slothkong/10-monkey-species).

## About
Our solution is built with transfer learning approach. 
We got VGG16 as pre-trained neural network with ImageNet's weights and by excluding last layer (Softmax), we decided to try a few traditional machine learning methods like Random Forest, SVM, Logistic Regression as a final classification tool.

## Results
According to kaggle solutions, our notebook surpassed most of them with 97% accuracy with Logistic Regression and SVM.

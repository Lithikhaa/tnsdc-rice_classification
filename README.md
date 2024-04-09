# tnsdc-rice_classification
rice classification using cnn
The [Original Dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset) contains 75000 images of 5 different Rice species. Each of the species has 15000 images each. The basic task is to develop a CNN model to classify a rice grain image into one of these 5 categories correctly.
Rice_Image_Classification
|
|--- Train
|     |---Arborio (12000 images)
|     |---Basmati (12000 images)
|     |---Ipsala (12000 images)
|     |---Jasmine (12000 images)
|     |---Karacadag (12000 images)
|
|--- Test/Validation
      |---Arborio (3000 images)
      |---Basmati (3000 images)
      |---Ipsala (3000 images)
      |---Jasmine (3000 images)
      |---Karacadag (3000 images)
Results
Performed prediction using Pre-trained ResNet-18. Accuracy on Training data = 17.805 % and that on Validation/Test data = 19.793 %
Trained ResNet-18 from scratch using Training dataset for 20 epochs. Train Accuracy = 99.95 % and Validation/Test Accuracy = 99.88 %


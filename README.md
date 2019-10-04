## Facial expression recognition using CNN

**Introduction:**

The goal of the project was to implement a classification algorithm that can automatically predict the categories of human expressions given human facial images. Facial expressions convey rich emotional information in human communication and interpersonal relations.Automatic facial expression recognition is a challenging problem and has many applications in multiple disciplines.
It has been proven that convolutional neural networks have advantages in object classification, especially for high-dimensional objects like faces.

**Dataset:** (https://www.consortium.ri.cmu.edu/ckagree/)

In this project, CNN models are trained on the Extended Cohn-Kanade (CK+) dataset to recognize 8 basic
emotions and neutral faces. We experimented different CNN architectures and methods such as dropout and batch normalization.

Steps to run code:
Step 1: Load prepare_data.ipynb 
Step 2: Download Emotion_labels.zip and extended-cohn-kanade-images from ck++ website : http://www.consortium.ri.cmu.edu/ckagree/ 
Step 3: Extract the data in one folder 
Step 4: Create two foders "final_dataset" and "stored_Set" 
Step 5: With in each folder create subfolders with names : anger, contempt, disgust, fear, happy, neutral, sadness and surprise. 
Step 6: Run prepare_data.ipynb

Results:

The final images will be stored in the foder: stored_Set train_images.npy, train_labels.npy, test_images.npy, test_labels.npy files which can be used to train and test Machine learning models will be created in the same folder.

Steps to run main CNN model:
Step 1: Load .npy files created before. 
Step 2: Load CNN_traintest.ipynb file. 
Step 3: Run CNN_traintest.ipynb

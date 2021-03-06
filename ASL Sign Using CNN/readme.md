# ASL Alphabet
*Image data set for alphabets in the American Sign Language* 
### Model is trained using Tensorflow 1.x Low-Level API
***From Kaggle : [ASL DATASET](https://www.kaggle.com/grassknoted/asl-alphabet)*** 

### **About**
The data set is a collection of images of alphabets from the American Sign Language, separated in 29 folders which represent the various classes.

### **Content**
The training data set contains 87,000 images which are 200x200 pixels. There are 29 classes, of which 26 are for the letters A-Z and 3 classes for SPACE, DELETE and NOTHING.
These 3 classes are very helpful in real-time applications, and classification.
The test data set contains a mere 29 images, to encourage the use of real-world test images.(NOTE : About and Content taken from the Dataset Website)

![asl.jpg](asl.jpg?raw=true "Title")
### File

**ASL.ipynb** : Jupyter Notebook for Processing Images, creating a Convolutional Neural Network, Training the Network and calculating Loss and Accuracy.

**ASL using Tensorflow.py** : This **.py** file contains the same code as in **ASL.ipynb**

### Result

***Loss and Accuracy :***

![loss.PNG](loss.PNG?raw=true)


# X-Ray Scans(pneumonia detection) 
#### The dataset used is this [Kaggle Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
![Capture.PNG](utils/Capture.PNG?raw=true "Title")

### About the Dataset
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert. (__From kaggle about data__)

## About the files

- Chest_X_Ray_Images_(Pneumonia).ipynb : __Jupyter Notebook containing Convolution Neural network build using Tensorflow low level API (tensorflow 1.x)

- chest_x_ray_images_(pneumonia) : __Python file containing Convolution Neural network build using Tensorflow low level API (tensorflow 1.x)

### Network Architechure (from TensorBoard)

![asd](utils/net.PNG?raw=true)

### Training loss and Validation loss (from TensorBoard)

![asd](utils/result.PNG?raw=true)



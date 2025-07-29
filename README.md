Deep Learning-Based Cat and Dog Breed Classification
**Overview**
This project aims to automatically classify cat and dog breeds using deep learning and transfer learning techniques. Leveraging the Oxford-IIIT Pet Dataset, we implemented a robust pipeline for data preprocessing, augmentation, and model training with state-of-the-art pretrained convolutional neural networks (CNNs).

**__Sample Results__**
Below is a sample grid of images from the dataset, featuring a variety of cat and dog breeds used in model training and evaluation:


Project Workflow
__Data Preparation__

Download images and annotations from the Oxford-IIIT Pet Dataset.

Preprocess images (resize, normalization, label encoding).

Visualize class distributions and sample images.

__Data Augmentation__

Apply techniques such as rotation, zoom, and flipping to increase dataset diversity.

__Model Training__

Experiment with multiple pretrained CNN architectures:

-MobileNetV2

-ResNet50

-EfficientNetV2-S

Xception (customized and fine-tuned)

Train with early stopping and model checkpointing for optimal results.

__Evaluation__

Assess performance with classification reports, accuracy metrics, and visual inspection of predictions.

Key Features
Transfer Learning: Utilizes powerful pretrained models for improved performance on limited datasets.

Data Visualization: Helps understand dataset balance and model predictions.

Augmentation Pipeline: Prevents overfitting and improves generalization.

Custom Training Loops: Includes advanced training strategies (freezing/unfreezing layers, batch normalization, dropout).

How to Run? -->
1-Install required packages:
pip install tensorflow tensorflow-hub matplotlib scikit-learn

2-Run the notebook or Python script to start data download, preprocessing, and training.
3-To visualize results, check the output plots and use the included evaluation functions.

Dataset
Source: Oxford-IIIT Pet Dataset

Content: -->
<img width="818" height="847" alt="image" src="https://github.com/user-attachments/assets/355b18a1-893a-4229-a768-55f1bf1896ec" />


Results
The project demonstrates high accuracy in breed classification and robust generalization across unseen data, thanks to advanced deep learning and augmentation techniques.



# Identifying Queenlessness in Honeybee Hives from Audio Signals

This project focuses on identifying queenlessness in honeybee hives using audio signal analysis. Queenlessness refers to the absence of a queen bee in a hive, which can have significant implications for the health and productivity of the colony. By analyzing audio recordings from the hive, this project aims to develop a machine learning model that can accurately detect queenlessness based on specific acoustic patterns.

## Dataset

The dataset used for this project can be accessed through the following link: 
- [Audio Dataset](https://drive.google.com/file/d/1utZiU31JF-4cbJmXlLeU_qZ0O8Y_2nQj/view?usp=sharing)
- [Numpy Dataset](https://drive.google.com/file/d/1iQjGGLkABK1h2AxnYix5G0JHjo4YNvTr/view?usp=sharing)

The audio dataset consists of 20000 audio recordings (14000 for training, 4000 for tesing and 2000 for traing) captured from honeybee hives, containing a mix of normal hives and hives without a queen. And the Numpy (NPY) dataset consists of Npy data after preprocessing.
## Code

The code for this project is organized as follows:

- `stft.ipynb`: This script is responsible for preprocessing the audio dataset, feature extraction.

- `1D_CNN_model_STFT_97_5ACC.ipynb`: This script trains the machine learning model using the preprocessed audio features. It employs algorithms and techniques suitable for audio signal classification, such as convolutional neural networks (CNNs).

## Usage

To use this code, follow these steps:

1. Download the audio dataset from the provided link.

2. Run the `stft.ipynb` script to preprocess the audio recordings and extract relevant features.

3. Execute the `1D_CNN_model_STFT_97_5ACC.ipynby` script to train the machine learning model using the preprocessed audio features.

Feel free to explore and modify the code according to your requirements. Happy detecting!

## [Model Architecture](https://drive.google.com/file/d/1yatezliW9On48Iq85e2Wr_NOTu_M7gGP/view?usp=sharing)
<div align="center"> <img src=1D_CNN_Model_975acc.h5.png>< </div>

## Result
- Accuracy plot:
<div align="center"> <img src=accuracy_plot.png> </div>
- ROC curve:
<div align="center"> <img src=ROC_curve_plot.png> </div>
- Confusion matrix:
<div align="center"> <img src=confusion_matrix.png> </div>
- Classification report:
<div align="center"> <img src=trainingsetstats.png> </div>


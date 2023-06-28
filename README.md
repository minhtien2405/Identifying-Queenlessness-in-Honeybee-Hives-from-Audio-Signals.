# Identifying Queenlessness in Honeybee Hives from Audio Signals

This project focuses on identifying queenlessness in honeybee hives using audio signal analysis. Queenlessness refers to the absence of a queen bee in a hive, which can have significant implications for the health and productivity of the colony. By analyzing audio recordings from the hive, this project aims to develop a machine learning model that can accurately detect queenlessness based on specific acoustic patterns.

## Dataset

The dataset used for this project can be accessed through the following link: 
- [Audio Dataset](https://drive.google.com/file/d/1utZiU31JF-4cbJmXlLeU_qZ0O8Y_2nQj/view?usp=sharing)
- [Numpy Dataset](https://drive.google.com/file/d/1iQjGGLkABK1h2AxnYix5G0JHjo4YNvTr/view?usp=sharing)

The audio dataset consists of audio recordings captured from honeybee hives, containing a mix of normal hives and hives without a queen. And the Numpy (NPY) dataset consists of Npy data after preprocessing.
## Code

The code for this project is organized as follows:

- `stft.ipynb`: This script is responsible for preprocessing the audio dataset, including noise removal, audio segmentation, and feature extraction.

- `model_training.py`: This script trains the machine learning model using the preprocessed audio features. It employs algorithms and techniques suitable for audio signal classification, such as convolutional neural networks (CNNs) or recurrent neural networks (RNNs).

## Usage

To use this code, follow these steps:

1. Download the audio dataset from the provided link.

2. Run the `data_preprocessing.py` script to preprocess the audio recordings and extract relevant features.

3. Execute the `model_training.py` script to train the machine learning model using the preprocessed audio features.

4. Once the model is trained, run the `model_evaluation.py` script to evaluate its performance on the test set and assess its ability to identify queenlessness in honeybee hives.

Feel free to explore and modify the code according to your requirements. Happy detecting!

## License

This project is licensed under the [MIT License](LICENSE).

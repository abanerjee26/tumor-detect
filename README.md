# Tumor Detect

This project aims to detect tumors and their type from an MRI scan of the brain.

## Dataset

The "Brain Tumor MRI Dataset" from Kaggle is used as both training and testing data. This is included in the `dataset` folder. Copy it to the root of your Google Drive to run the code.

## Dependencies

Create and activate a new virtual environment using venv.

```sh
$ python -m venv venv  # Or python3
$ ./venv/Scripts/Activate.ps1  # . ./venv/bin/activate for Linux or Mac
```

To install all dependencies, run:

```sh
$ pip install -r requirements.txt
```

## Paper

https://ieeexplore.ieee.org/document/10397907

Cite using:

```
A. Banerjee, K. Jaiswal, T. Biswas, V. Sharma, M. Bal and S. Mishra, "Brain Tumor Detection and Classification Using a Hyperparameter Tuned Convolutional Neural Network," 2023 6th International Conference on Contemporary Computing and Informatics (IC3I), Gautam Buddha Nagar, India, 2023, pp. 502-506, doi: 10.1109/IC3I59117.2023.10397907.

Keywords: Convolution, MRI, Brain Cancer, Brain Modeling, CNNs, Tumors, RNNs, Brain Tumor Detection, Data Pre-Processing, Prediction
```



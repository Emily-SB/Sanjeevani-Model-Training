# Sanjeevani – Medicinal Plant Classification

This repository contains the deep learning notebooks used for training and evaluating different CNN models for the **Sanjeevani medicinal plant identification project**.

The models were trained on the **Indian Medicinal Leaves Dataset** and compared for their performance in medicinal plant classification.

## Models

The following models were trained and evaluated:

* EfficientNet-B0
* MobileNetV2
* ResNet18
* ShuffleNet

## Dataset

The project uses the **Indian Medicinal Leaves Dataset** available on Kaggle.

Dataset: `aryashah2k/indian-medicinal-leaves-dataset`

The dataset is downloaded directly in the Google Colab notebooks using `kagglehub`.

## Notebooks

| Notebook               | Purpose                                    |
| ---------------------- | ------------------------------------------ |
| `EfficientNetB0.ipynb` | Training and evaluation of EfficientNet-B0 |
| `MobileNetV2.ipynb`    | Training and evaluation of MobileNetV2     |
| `ResNet18.ipynb`       | Training and evaluation of ResNet18        |
| `ShuffleNet.ipynb`     | Training and evaluation of ShuffleNet      |

The notebooks include dataset loading, preprocessing, model training, validation, and image prediction. Evaluation notebooks/cells also include confusion matrix generation where applicable.

## Training

The images are resized to **224 × 224 pixels** and normalized using ImageNet mean and standard deviation.

The dataset is divided into:

* 80% training
* 20% validation

The models are trained using **PyTorch**.

## Technologies Used

* Python
* PyTorch
* Torchvision
* KaggleHub
* Google Colab
* Matplotlib
* PIL

## Project

These notebooks form the model-training component of the **Sanjeevani** project, an AI-based medicinal plant identification system.

The trained model was later used as part of the Sanjeevani application.


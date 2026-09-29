# Computer Vision Cancer Detection

A convolutional neural network (CNN) for detecting cancer from medical images, built with deep learning in Python. The project trains and evaluates an image classifier to distinguish between cancerous and non-cancerous samples.

> **Disclaimer:** This project is for research and educational purposes only. It is not a medical device and must not be used for clinical diagnosis or treatment decisions.

## Repository Contents

| File | Description |
|------|-------------|
| `Cancer_Detection_CNN.ipynb` | Notebook covering data loading, preprocessing, CNN training, and evaluation |
| `README.md` | Project documentation |

## Overview

- **Task:** binary image classification (cancer vs. non-cancer)
- **Approach:** CNN trained on labeled medical images
- **Dataset:** _add dataset name, source link, and image count_
- **Framework:** _TensorFlow/Keras or PyTorch_

## Workflow

1. **Data loading:** read the image dataset and labels.
2. **Preprocessing:** resize, normalize, and split into train/validation/test sets.
3. **Augmentation:** apply flips, rotations, and zooms to reduce overfitting.
4. **Model:** build and train a CNN classifier.
5. **Evaluation:** measure performance on unseen test data.
6. **Analysis:** review the confusion matrix, ROC curve, and misclassified examples.

## Getting Started

### Prerequisites

- Python 3.9+
- Jupyter Notebook, JupyterLab, or Google Colab (GPU recommended)

### Installation

```bash
git clone https://github.com/TimBroAhm/Computer-Vision-Cancer-Detection.git
cd Computer-Vision-Cancer-Detection
pip install numpy pandas matplotlib scikit-learn tensorflow jupyter
```

### Run

```bash
jupyter notebook Cancer_Detection_CNN.ipynb
```

Or upload the notebook to Google Colab, enable a GPU (Runtime → Change runtime type), and run all cells.

## Results

<!-- Add your metrics and plots here, e.g.: -->
<!-- ![Confusion matrix](images/confusion_matrix.png) -->

| Metric | Value |
|--------|-------|
| Accuracy | – |
| Precision | – |
| Recall (Sensitivity) | – |
| F1-score | – |
| AUC | – |

## Future Work

- Try transfer learning (ResNet, EfficientNet, DenseNet)
- Add explainability with Grad-CAM to highlight the regions driving each prediction
- Evaluate on external datasets to test generalization
- Address class imbalance with weighting or resampling

## Tech Stack

Python · TensorFlow/Keras · NumPy · Pandas · Matplotlib · Scikit-learn · Jupyter

## Author

**Tim** ([@TimBroAhm](https://github.com/TimBroAhm))

## License

Add a license (e.g., MIT) to clarify how others can use this work.

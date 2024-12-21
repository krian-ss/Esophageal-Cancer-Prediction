
## Project Contributors

[@krian-ss](https://www.github.com/krian-ss), [@harshaygadekar](https://www.github.com/harshaygadekar),
[@manoj8541](https://www.github.com/manoj8541),[@atharv6411](https://www.github.com/atharv6411) .



## License

[Apache-License 2.0](https://www.apache.org/licenses/LICENSE-2.0)


# Esophageal Cancer Detection Using Tensorflow and EfficientNetB7

This project implements a deep learning model for binary classification of esophageal cancer using endoscopy images. It utilizes transfer learning with EfficientNetB7 as the base model, built on TensorFlow and Keras. The model is trained on a dataset of endoscopy images, categorized into 'esophagus' and 'no-esophagus' classes.

The code handles data preparation, model creation, training, and result visualization, providing a complete pipeline for esophageal cancer detection from medical imaging data.

## Features Include


- Transfer learning with EfficientNetB7
- Data augmentation using ImageDataGenerator
- Binary classification (cancer/no cancer)
- Visualization of training and validation metrics
- Model saving for future use
- Prediction of cancer
  

## Tech Stack Used

Python, Tensorflow, Keras APIs, Pandas, Numpy, EfficientNetB7, Matplotlib, Jupyter Notebook.


## Installation

### Requirements:

Download the dataset from https://www.kaggle.com/datasets/chopinforest/esophageal-endoscopy-images

### Install Python: 
Download and install Python from https://www.python.org/downloads/

### Install Jupyter Notebook:
Open a terminal or command prompt and run:

```bash
pip install jupyter
```

### Install Required Dependencies:

```bash
pip install tensorflow pandas numpy matplotlib scikit-learn opencv-python
```


### Execution:

- Download the Jupyter Notebook from this repository.
- Specify the directory path and image path
- Specify the number of images to train the model.
- Run each code cells from the beginning.
  

## Future Enhancements

- Multi-class classification: Extend the model to classify different stages or types of esophageal cancer.
- Explainable AI: Implement techniques like Grad-CAM to visualize which parts of the image the model focuses on for its predictions.
- Web application: Develop a user-friendly web interface for medical professionals to upload and analyze images.




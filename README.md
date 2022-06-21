
# Image Classification Using CNN and Keras

This code pattern demonstrates how images can be classified using Convolutional Neural Network (CNN). Even though there are code patterns for image classification, some of them do not showcase how to use CNN to classify images using Keras libraries. Two class of images(phones and sunglasses) were collected from colleagues for the project.


## Overview video of how it works

https://youtu.be/HGwBXDKFk9I


## Installation

Install tensorflow and create a virtual enviroment using
Installation Instructions from https://developer.apple.com/metal/tensorflow-plugin/

    
## Roadmap

- Data pre-processing

- Configure the dataset for performance #OPTIONAL

- Data augmentation. More useful when you work with less data

- Rescale pixel values

- Create a base model from the pretrained convnets and extract feartures. Or create your own model with weights from scratch

- Compile the model. Important step before training of the model

- Train the model

- Fine tune pretrained model if accuracy is low for better accuracy

- Compile the fine tuned model

- Train fine tuned model

- Evaluate model on test dataset and,

- Make prediction to classify the images






## Deployment

To deploy this project:
- activate your virtual enviroment
```bash
  conda activate <env name>
```

- pip or conda install opencv
```bash
  conda install opencv
```

- navigate to folder containing "capture.py" file

- run the "capture.py" file
```bash
  python capture.py
```

- expect your camera to open if all installations were done properly

```bash
  tap on your spacebar to capture image. The image class will be predicted.
```


## Screenshot of predicted images

![App Screenshot](https://raw.githubusercontent.com/joRic20/CNN_and-Keras_for_Image-classification/main/Screenshot%202022-06-21%20at%2015.08.24.png)

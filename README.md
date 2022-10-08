
# Mask Detector Project

This project aims to detect whether the person in the video feed is wearing
Mask or not by implementing MobileNetv2 in the deep learning model and deploy it in 
web application with Flask

# Details 

- train deep learning model using mobileNetv2 with dataSet from kaggle
- develop an web interface using Flask


## Technologies

* Python
* MobileNetv2
* OpenCV
* Flask


## DataSet

The dataset used for training the model is from :

https://www.kaggle.com/datasets/omkargurav/face-mask-dataset


## Usage

You have to install the required packages, you can do it:
* via pip
```bash
  pip install -r requirements.txt
```

Then to run the application you need to insert the next commands :
```bash
  $env:FLASK_APP="main.py"
```
```bash
  flask run
```


# Getting Started
A Webapp to detect Skin and Brain Tumor using dermoscopic images and  MRI scans Using Deep Learning

![image](https://user-images.githubusercontent.com/66179774/148924061-d8f462f9-cb2b-4699-b9f4-b7f92f461ae5.png)

# Languages & Frameworks Used
- Python
- Javascript
- HTML
- CSS
- Bootstrap
- Flask
- sklearn
- tensorflow
- pillow
- open-cv

# Installation
## Step One
  Download and Extract the Datasets From The links Below
  1. [BRAIN MRI SCANS ](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
  2. [SKIN DERMOSCOPIC IMAGES ](https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign)
## Step Two
Download, Extract and open this project using a code editor
## Step Three
Installation of the Libraries
<img width="960" alt="Screenshot 2022-01-11 161107" src="https://user-images.githubusercontent.com/66179774/148928162-e2d50a0d-bb2a-4993-95ab-ac68d785ae05.png">
```
pip install opencv-python
```
```
pip install pillow
```
```
pip install sklearn
```
```
pip install tensorflow
```
```
pip install flask
```
## Step Four
Update  the image directory path in the maintrain_brain.py and mainTrain.py file
**The directory path in the mainTrain.py file should be of skin cancer folder**
**The directory path in the mainTrain_brain.py file should be of Brain MRI Scans folder**
<img width="956" alt="Screenshot 2022-01-11 161949" src="https://user-images.githubusercontent.com/66179774/148930901-8a91f730-114e-48b0-b5e5-aa22de422368.png">
**Dont forget to use forward slash in the directory path as shown in the image below or else would result in a error**
## Step Five
**Training the Model**
Run the MainTrain_Brain.py and MainTrain.py files one by one.
<img width="287" alt="Screenshot 2022-01-11 162929" src="https://user-images.githubusercontent.com/66179774/148931012-3633e5dc-d470-4538-bee2-4b5135e6b72b.png">
**The Maintest files can be used for testing the output result**

## Step Six 
Run the App.py file.
**The Model will be loaded on a local server at http://127.0.0.1:5000/**
<img width="958" alt="Screenshot 2022-01-11 162837" src="https://user-images.githubusercontent.com/66179774/148931102-55e80e13-f214-4f79-9420-9d597643f78b.png">
## Step Seven
**Upload the Test Images to get the Output**

<img width="955" alt="Screenshot 2022-01-11 162747" src="https://user-images.githubusercontent.com/66179774/148931208-96cf937a-f967-4988-8120-5b0a33739b34.png">

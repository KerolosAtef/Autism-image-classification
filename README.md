# Autism-image-classification
![Original test set](https://drive.google.com/uc?export=view&id=1y0eCa6zf96n5YZgOfFPoRtpEoYs8fNS4)

## Overview
This project amis to classify between persons autistic and non-autistic and this classification depends on their photos.<br>
This project uses a pretrained models like efficient net and Vgg and inception model for image classification task.<br>

## Dataset 
This dataset is downloaded from kaggle datasets

## Important libraries 
```python
pip install tensorflow-gpu==2.9.1 
pip install skimage 
pip install PIL 
pip install numpy 
pip install shutil
pip install argparse
```
## Project main flow
- Data preprocessing and augmentation 
- Load pretrained models and finetune them with the task data 
- Chose the champion model between (Vgg,Inception,EfficientNet)

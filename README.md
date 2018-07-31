# Convolutional Neural Network

In this project I'll show you example of using simple convolutional neural networ for image recognition.

Used images come from Keggle:

https://www.kaggle.com/paultimothymooney/breast-histopathology-images/version/1

Images description:

"Invasive Ductal Carcinoma (IDC) is the most common subtype of all breast cancers. To assign an aggressiveness grade to a whole mount sample, pathologists typically focus on the regions which contain the IDC. As a result, one of the common pre-processing steps for automatic aggressiveness grading is to delineate the exact regions of IDC inside of a whole mount slide. The original dataset consisted of 162 whole mount slide images of Breast Cancer (BCa) specimens scanned at 40x. From that, 277,524 patches of size 50 x 50 were extracted (198,738 IDC negative and 78,786 IDC positive). Each patch’s file name is of the format: u_xX_yY_classC.png — > example 10253_idx5_x1351_y1101_class0.png . Where u is the patient ID (10253_idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC. The data and traning/test set partitions can be downloaded from: http://gleason.case.edu/webdata/jpi-dl-tutorial/IDC_regular_ps50_idx5.zip"

Before you head to the notebook make sure you've got all necessary packages installed. If you're missing some of them use these commands:

```javascript
pip install --upgrade --no-deps git+git://github.com/Theano/Theano.git
pip install --upgrade keras
```

or
```javascript
sudo pip install --upgrade --no-deps git+git://github.com/Theano/Theano.git
sudo pip install --upgrade keras
```

Install Tensorflow from the website: https://www.tensorflow.org/versions/r0.12/get_started/os_setup.html

Every feedback is welcome. Enjoy.
### Kacper Turek

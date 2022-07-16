# Natural_Plastic_Surgery

![alt text](https://github.com/syeminpark/Natural_Plastic_Surgery/blob/main/readmeImage.jpg?raw=true)

### Story
A device + algorithm to help anyone practice strecthing their eyelids 
in the hope of making their eyes bigger in a natural?(zero budget) way.

As long as your eyes are opened bigger than the criteria, the device's motor 
activates and pumps apple juice as a prize. 
  

### Process

1. HaarCascade to detect face
2. Dlib Shape Detector to detect eyes and crop region
3. CNN to classify of eyes are opened or closed


  
### Dataset
Closed Eyes In The Wild
  


### Physical Computing
Arduino & pySerial
  

  
### Based On
https://medium.com/@iaswnparaskev/a-simple-blink-detector-using-a-small-convolutional-neural-network-with-python-ba8171ae0e0b 
  

  
### File
dataset.csv - Dataset.  
blinkModel.hdf5 - Model trained on the eyes Open/Closed Dataset.   
natural_plastic_surgery.py - main code.     
shape_predictor_68_face_landmarks.dat - 68 points in face.  
haarcascade_frontalface_alt.xml - face detection model. 

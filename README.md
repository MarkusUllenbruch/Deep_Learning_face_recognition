# Deep Learning Face Recognition
## Transfer Learning based classifier of faces

# 0. Overview
 Building a deep learning face recognition system using transfer learning.
 The classifier can classify

 - my own face "Markus"
 - faces of other human beings "others"
 - some random "objects".
 <img align="left" src="Plots/Markus.PNG" width="100">
 <img align="left" src="Plots/Others.PNG" width="100">
 <img align="left" src="Plots/Objects.PNG" width="100">
 <br />
 
 
 # 1. Data
 
 <p align="center">
  <img src="Plots/Info.PNG">
</p>
 
# 2. Results
Even if my brother who is looking a lot like me is not available in the whole dataset the classifier is trained on, most pictures of my brother are classified correctly as "Others".
## 2.1 Confusion Matrix on Validation and Test Dataset
<img src="Plots/cm.PNG" width="350"> <img src="Plots/cm_test.PNG" width="350">

## 2.2 Training & Validation Accuracy
<p align="center">
  <img src="Plots/acc.PNG" width="400">
</p>



# 3. Additional Info
To train with your own data you have to fill the Dataset folder with your own images and images of objects and other human faces.
To train on other categories than your face, others and objects, you can adapt the code and the dataset folder containing the images to your own data categories.
The code is very well documented with markdown cells containing explanations and the code has many comments.

If you find some issue or you have quastions about the code or the topic, please contact me via e-mail :)

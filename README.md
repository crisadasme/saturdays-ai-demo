# BATTERIA - SATURDAYS AI PROJECT

This repository contains final code developed for final projects of Saturdays AI Santiago 2019. 

# # Starting 🚀 
### About BatterIA!

The goal of Saturdays AI Santiago was focused on allowing their students to use data science tools and artificial intelligence models in projects with positive social impact. In the team named BatterIA which I participated, we opted to make a possible solution for ecological sector, opting to training an intelligent model capable of identifying lithium cells batteries that were not properly recycled being separating them from the rest of the waste.

## # How it Works? 🔧
This model was developed in Pytorch and also we opted to use a pretrained model named YOLO which is currently the state of art in multiple object detection.

We created a Custom Dataset downloading by script about 1000 Images of lithium cells and we trained the model using commons training params.


* Learning Rate : 2e-5
* Epochs : 273  
* Batch Size : 16
* Optimizer : Adam

**Note**: All parameters used are specified in train.py, but all this configuration are detailed in the original implementation of YOLO for Pytorch.


# # Final Comentary:
Despite the fact that the project works wonderfully and perfectly fulfills the goal for which it was designed. We have detected some details both to correct and to continue developing in the future.


### TO DO 📑
* Possibility of expanding the number of classes to detect different types of waste at the same time.

* Increase detection accuracy by increasing the number of images for the training data set.

* Add Data Augmentation to training Dataset.

* Use original yolov3 settings and weights to compare results already obtained by current config.


# # Preview
<p float="left">
 <img src="batteria.gif" />
</p>


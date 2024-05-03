# UNO CARDS DETECTION USING YOLOV5 


### OVERVIEW : 
The purpose of this project is to create a Deep Learning model that detect the Uno cards . My model is based on YOLO's object detection algorithm, and I'm using the dataset from Roboflow website.



 ## 📁DATA COLLECTION:
 
**UNO DETECTION**: **https://universe.roboflow.com/dtcinfotech-eyt5v/uno-sajey**
  
 ## BUSINESS CASE:TO BUILD A SYSTEM FOR DETECTING THE UNO CARDS FOR GIVING THE IMAGES

**The dataset consists of 14  classes:**
nc: 14
names: ['0', '10', '11', '12', '13', '14', '2', '3', '4', '5', '6', '7', '8', '9']

![image](https://github.com/Tanwar-12/UNO-CARDS-DETECTION-USING-YOLOV5/assets/110081008/14548228-049c-47a2-9ee3-900c1d06f7f8)



# WORKFLOW:
  ## Data Preparation:
  * Total 200 images for training and for validation present in 14 classes.
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
  ![train folders](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/69b19a8e-2f81-4d9b-a762-ffa73ac59be1)
## STEPS TO USE YOLOV5: 
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.

 ## STEPS BEFORE TRAINING CUSTOM DATASET :
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.

  ## TRAINING YOLOV5 MODEL:
* Set images size 640 with batch of 8.
* Train model around 600 epochs .
* Visualise the training metrics with the help of tensorboard.

 ## TESTING IMAGES USING TEST DATA:
![image](https://github.com/Tanwar-12/UNO-CARDS-DETECTION-USING-YOLOV5/assets/110081008/8e15d03d-6125-4e3e-834b-185443d5158d)
![image](https://github.com/Tanwar-12/UNO-CARDS-DETECTION-USING-YOLOV5/assets/110081008/519ca110-400c-4aab-be55-8c52f22e5d63)
![image](https://github.com/Tanwar-12/UNO-CARDS-DETECTION-USING-YOLOV5/assets/110081008/b08fc11c-bb89-4ef5-883d-81955d9cf762)
![image](https://github.com/Tanwar-12/UNO-CARDS-DETECTION-USING-YOLOV5/assets/110081008/588b4641-8150-4173-92b5-361e19485b98)

## TESTING VIDEO DEMO :

  

https://github.com/Tanwar-12/UNO-CARDS-DETECTION-USING-YOLOV5/assets/110081008/f7fe86bb-95fa-487f-8799-d28052c8cea3











## Custom-training-of-YOLOV3-model-for-object-detection
Here, I have trained the yolo model for 2 classes (wearing mask and not wearing mask). For training this model, I have used the darknet files from the internet and did modification in cfg files for 2 classes object detection

Darknet files with weights and cfg can be downloaded from 
https://github.com/AlexeyAB/darknet


This project was inspired from the youtube channel video

https://www.youtube.com/watch?v=_FNfRtXEbr4&t=918s


In this project, I have used the python google colab complier to make use of the google fast free GPU.  

## Techniques: transfer learning

Transfer learning is the process of retraining a pretrained network to classify a new set of images. The components needed for transfer learning are: pretrained network layers, training data, and algorithm options. This activity reviews creating the datastore and the training options so that you can perform transfer learning with darnet network.

Pretrained networks can classify images into predetermined categories. The data set in this project contains specification of with mask and without mask, and the pretrained network has not been trained on these classes. Instead of starting from scratch, I had modified a pretrained network to fit this project.


## Dataset
For this python project, I had used theFace Mask Detection; the dataset is available in the public domain and you can find from below link. This dataset serves as a benchmark for face photos with and without mask and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. It has a total of 853 photos. For labelling the dataset, I used LabelImg - https://tzutalin.github.io/labelImg/ to separate the images classes as 0 and 1 (without mask and with mask)

## Results

![with_mask](https://user-images.githubusercontent.com/71879067/126141579-631e12f6-fc00-4609-97ad-cec332ea54db.JPG)
![without_mask](https://user-images.githubusercontent.com/71879067/126141598-aadd9773-6f26-43da-ab61-e0339b35f25e.JPG)


![ezgif com-gif-maker](https://user-images.githubusercontent.com/71879067/126660801-7009d3d0-424a-47f8-ba3d-a513561cabc0.gif)




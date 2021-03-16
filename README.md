# FRCNN-on-wheat-images

Implemtation of FRCNN (fast region-based convolutional neural networks) on wheat images in pytorch

It was a kaggle competition. I mainly doing it for fun. 

The number on top of red boxes are possibilities of wheats

The FRCNN.ipynb used FastRCNNPredictor (torchvision.models.detection.faster_rcnn) with pretrained weitght 

and trained than trained 30 min with GTX 1080ti 

![Train result](https://github.com/ShangChunLin/FRCNN-on-wheat-images/blob/main/FRCNN.png)

The FRCNN_scratch.ipynb used pretrained resnet50 as backbone, and rest from sort of from scratch

![Train result](tba)


The training notebooks are under folder NN, and the training/testing data are in my google drive (https://drive.google.com/file/d/1f7O0mVL6w4R93rEIBTqIoXc30D4SJHBZ/view?usp=sharing)

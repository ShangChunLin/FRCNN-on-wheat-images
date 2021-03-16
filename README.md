# FRCNN-on-wheat-images

Implemtation of FRCNN (fast region-based convolutional neural networks) on wheat images in pytorch

It was a kaggle competition. I mainly did it for fun. 


The FRCNN.ipynb used FastRCNNPredictor (torchvision.models.detection.faster_rcnn) with pretrained weitght 

and than trained 30 min with GTX 1080ti 


The red boxes are predict result and number on top of them are possibilities of wheats

![Train result](https://github.com/ShangChunLin/FRCNN-on-wheat-images/blob/main/FRCNN.png)

The FRCNN_scratch.ipynb used pretrained resnet50 as backbone, and rest from sort of from scratch

![Train result](https://github.com/ShangChunLin/FRCNN-on-wheat-images/blob/main/scratch_example_view.png)


The training notebooks are under folder NN, and the training/testing data are in my google drive (https://drive.google.com/file/d/1f7O0mVL6w4R93rEIBTqIoXc30D4SJHBZ/view?usp=sharing)

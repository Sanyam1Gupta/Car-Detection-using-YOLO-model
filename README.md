# Car Detection Using YOLO Model

The goal is to detect 'cars' in images using the YOLO model(You Only Look Once model).Compared to other region proposal classification networks 
(fast RCNN) which perform detection on various region proposals and thus end up performing prediction multiple times for various 
regions in a image, Yolo architecture is more like FCNN (Fully Convolutional Neural Network) and passes the image (nxn) once 
through the FCNN and output is (mxm) prediction. Thus the architecture is splitting the input image in mxm grid and for each 
grid, generates 2 bounding boxes and class probabilities for those bounding boxes. 
(This mini-project is a part of Deep Learning specialization course. The dataset, any pre-trained weights/models and Model Architecture used were provided by Coursera.)

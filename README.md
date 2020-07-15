## face_mask_detection

The main purpose of this project is to detect if a person is wearing a mask or not in real time.

### Algorithm used

Yolov4 is the latest version of the well recoginzed YOLO algorithm in the computer vision community. 
This algorithm is the state of the art in real time object detection with considerable high accuracy at high fps.
I used transfer learning on this algorithm with the help of Yolov4 weights. These weights are obtained by training on large ImageNet dataset.
Darknet is the deep learning framework used in this notebook.

### Custom Dataset preparation

Images are downloaded from the google images with the help of browser extension to download large number of images automatically.
Bounding box and label annotation is done on the makesense.ai website manually. makesense.ai website is very convinient and easy to annotate the data.

### Training Yolov4

To train we have to create 3 files.
1. obj.names
2. obj.data
3. our custom .cfg file








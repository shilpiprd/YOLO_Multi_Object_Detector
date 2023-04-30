# YoloV3
________
A Yolo model which recognizes all 80 classes presnet in the original cocos.names dataset. 


_A Collage of Training images_
![image](https://github.com/shilpiprd/YOLO_Multi_Object_Detector/blob/master/output/collage_download.jpeg)
<img src="https://raw.githubusercontent.com/shilpiprd/YOLO_Multi_Object_Detector/master/output/collage_downloaded" alt="Image" width="1234" height="1600">

In this project, I'm using pretrained weights and configuration file.
Follow these steps to successfully run the colab file. 
1. Download the weights folder from the link: https://pjreddie.com/media/files/yolov3.weights  and rename it as yolov3.weights. 
  * to save time, move the file from the above link to your GDrive
  * then drag and drop from your GDrive opened in Colab to YOLO_Multi_Object_Detector folder.

For trying out one of your own images,
1. Download an image, drag and drop it from ur GDrive opened in Colab to YOLO_Multi_Object_Detector folder.
2. copy one of the cells under heading 'Object Detection.' and change the name of image in cv2.imread with your image name.
3. The output would be saved in ouput.out_out folder. 


The classes which would be recognized by this model are present in the coco.names. 

**Results**
After running the image through the model, results look awesome!

![image](https://github.com/shilpiprd/YOLO_Multi_Object_Detector/blob/master/output/download2.png)
<img src="https://raw.githubusercontent.com/shilpiprd/YOLO_Multi_Object_Detector/master/output/download2.png" alt="Image" width="1024" height="1024">

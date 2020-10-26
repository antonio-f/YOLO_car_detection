# YOLO Car Detection

Works on a conda environment with TensorFlow 1.14.0 + Keras.

Important: you have to put the file yolo.h5 in the model_data folder. The file is ~196MB and can be obtained following these instructions:

1) clone or download YAD2K (https://github.com/allanzelener/YAD2K); 

2) download weights and cfg files (YOLOv2 608x608) from https://pjreddie.com/darknet/yolo ;

3) put the files in the YAD2K-master folder, open a shell, activate a TensorFlow 1.X + Keras environment and type 

python yad2k.py yolov2.cfg yolov2.weights model_data/yolo.h5 ;

4) put the yolo.h5 file in the model_data folder of the Car Detection project.

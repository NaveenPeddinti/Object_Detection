# Object_Detection
Object detection using You Only Look Once method 
##Command format
python opencv.py --image /path/to/input/image --config /path/to/config/file --weights /path/to/weights/file --classes /path/to/classes/file_

##Provided input files are in same directory, apply below command
python opencv.py --image input.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt`


Download the pre-trained YOLO v3 weights file from this [link](https://pjreddie.com/media/files/yolov3.weights) and place it in the current directory or you can directly download to the current directory in terminal using
 
 `$ wget https://pjreddie.com/media/files/yolov3.weights`

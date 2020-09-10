Requeriments:

openCV
pandas
numpy

Steps to run: 

1. Download or copy yolov3.weights to \yolov3-coco\ directory. It's available on https://pjreddie.com/media/files/yolov3.weights
2. Go to repos root directory, and open cmd or PowerShell on this folder.
3. Type python yoloV3.py -co=50 -tn=5. Where -co indicates the number of pictures in  .\im\   with "testXX.jpg" name format
  and -tn indicates the number of times that algoritm will be runned.
  
In .\ directory will be generated a series of CSV files, with each algorithm execution data (time of prediction, objects predicted, dimensions of image). 

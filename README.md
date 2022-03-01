# Pothole_detection
Custom trained yolov5 to perform pothole detection.
The first step involved preparation of dataset for which I collected around 100+ videos across various locations near my locality. 
Later images were extracted and pre-processed from those videos. At the end of data collection I had a total of 2000 images. 

These images were resized to one specific size and then all the images were annotated using make sense AI tool. After annotation I used pre-trained object detection model yolov5 to train a custom pothole detection model. After 200 epochs good accuracy was achieved.

Later this model was run on real time pothole videos recorded at various speeds (10kmph,20kmph,30kmph,40kmph). Detection performed at various speeds were compared and analysis were made. This object detection model can be deployed on a raspberry pi or any other compatible microprocessor.

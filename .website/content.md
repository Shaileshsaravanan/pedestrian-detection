this project explores pedestrian detection using opencv and a haar cascade classifier. the goal is to detect people in images or video streams, visualize the detections, and understand how classical computer vision handles this task.

## layout

**train/**  
contains positive and negative samples for training the cascade.

**test/**  
contains images or videos used to evaluate detection.

**main/**  
contains the working script `Pedestrian Detection.py`, which runs the detector on test inputs.

## requirements

you’ll need:

• python 3.x  
• opencv (cv2)  
• numpy

## what the script does

1 • loads the trained haar cascade  
2 • reads images or video  
3 • runs detection  
4 • draws bounding boxes  
5 • shows or saves the results  

## output

once it runs, you’ll see frames with bounding boxes around detected pedestrians. they can be displayed live or written back to the `test/` folder.

## notes

• verify the haar cascade xml file path in the script  
• accuracy depends heavily on dataset quality and the trained classifier
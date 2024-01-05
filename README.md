Face Detection python program using OpenCV library

Requirements:
-python3 above
-numpy
-argparser
-imutils
-opencv-python



How to use:

1.For image:
-Run: python face_detection.py --image [*insert your image here*] --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

Note: Use your image while running above line

2.For video:
-Run: python face_detection_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

Note:face detection in video used webcam and works on live video




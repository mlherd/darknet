# Darknet #
Original Wrok: [Darknet project website](http://pjreddie.com/darknet).

Test System:
   - Graphics Card: Nvidia GTX 1050Ti 4GB
   - CPU : Intel i5-3470
   - RAM: 12GB
   - ~25 FPS

Modified darknet.py
  - Use camera as source
  - Draw rectanges around the detected objects
  - Put a label on each object 

Modified files:
  - darknet.py
  - image.c
  - image.h
  - Makefile

Setup instructions:
 - Download a pre trained model in the main directory
   - wget https://pjreddie.com/media/files/yolov3.weights
- Follow Install Darknet Instructions for this repo
- Anaconda
   - Create an enviroment Python 3.6
   - Install OpenCV and Numpy Packages  
- make clean
- make

execute:
   - python darknet.py
   
   or 
   
   - ./darknet detector demo cfg/coco.data cfg/yolov3.cfg yolov3.weights

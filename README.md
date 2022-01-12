# Smart Classroom
Objective : The objective of this project is to automate the switching of Fans and lights 
without need for searching switches. In this system a Camera is used to capture 
images of the classroom/auditorium/factories. This images will be processed 
using Deep learning algorithm such as CNN using Yolo Algorithm trained using 
custom dataset.

Platform : Raspberry pi, Neural Networks, Image Processing

Language : Python

Components : Wifi Camera, Relays

Outcome : The output of the model contains the image where Head is detected with
bounding boxes. Depending on the position of Bounding boxes, the 
corresponding fans/lights are mapped to switch them on/off using relays.

#Framework code from 
Fork Darknet framework for YOLO net.

#Darknet#
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

#YOLO net Optimization and testing
1.launch picture detect
./darknet detector test cfg/coco.data cfg/yolo.cfg yolo.weights test.jpg

2.launch camera detect
./darknet detector demo cfg/coco.data cfg/yolo.cfg yolo.weights

3.launch video detect
./darknet detector demo cfg/coco.data cfg/yolo.cfg yolo.weights <video file>

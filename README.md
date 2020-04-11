## YOLO Object Detection

This project implements a real time object detection via image detection using YOLO algorithm. YOLO is a object detection algorithm which stand for You Only Look Once. I've implemented the algorithm from scratch in Python using pre-trained weights. YOLOv3 was published in research paper: <a href="https://pjreddie.com/media/files/papers/YOLOv3.pdf" rel="nofollow">YOLOv3: An Incremental Improvement: Joseph Redmon, Ali Farhadi</a> It's originally implemented in <a href="https://github.com/pjreddie/darknet">YOLOv3</a>.

COCO dataset is used for training.

Real time detection can be use via command prompt or GUI.

<table>
  <tbody>
	<tr align="center">
		<th><strong>A Gaming Cars Detection</strong></th>
	</tr>
	<tr align="center">
		<td><img src="https://github.com/muhammadshiraz/yolo_object_detection/blob/master/doc/detector1.jpg"></td>		
	</tr>
	<tr align="center">
		<th><strong>Real Cars Detection</strong></th>
	</tr>
	<tr align="center">
		<td><img src="https://github.com/muhammadshiraz/yolo_object_detection/blob/master/doc/detector2.jpg"></td>
	</tr>
	<tr align="center">
		<th><strong>Real Room Detection</strong></th>
	</tr>
	<tr align="center">
		<td style="width: 100%;"><img src="https://github.com/muhammadshiraz/yolo_object_detection/blob/master/doc/detector3.jpg"></td>
	</tr>
	<tr align="center">
		<th><strong>Real Walking Detection</strong></th>
	</tr>
	<tr align="center">
		<td style="width: 100%;"><img src="https://github.com/muhammadshiraz/yolo_object_detection/blob/master/doc/detector4.jpg"></td>
	</tr>
</tbody>
</table>

Yolo is a deep learning algorythm which came out on may 2016 and it became quickly so popular because it’s so fast compared with the previous deep learning algorythm.
With yolo we can detect real time objects at a relatively high speed. With a GPU we would be able to process over 45 frames/second while with a CPU around a frame per second.

OpenCV dnn module supports running inference on pre-trained deep learning models from popular frameworks like Caffe, Torch and TensorFlow.

## Requirement
<ul>
<li>OpenCV 4.2.0</li>
<li>Python 3.6</li>
</ul>

## Quick start
<ul>
  <li>Download official <a href="https://pjreddie.com/media/files/yolov3.weights" rel="nofollow">yolov3.weights</a> and place it under a folder called weight.</li>  
  <li>Download <a href="https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg">yolov3.cfg</a> and place it under a folder called cfg.</li>
</ul>

## Dependencies
<ul>
<li>opencv</li>
<li>numpy</li>
</ul>

## Install dependencies
<p><code>pip install numpy opencv-python</code></p>

## How to use?
<ol>
  <li>Clone the repository</li>
  <p><code>git clone https://github.com/muhammadshiraz/yolo_object_detection.git</code></p>
</ol>
<ol start="2">
  <li>Move to the directory</li>
  <p><code>cd yolo_object_detection</code></p>
</ol>
<ol start="3">
  <li>To view the Gaming Cars Detection</li>
  <p><code>python yolo_object_detection1.py</code></p>
</ol>
<ol start="4">
  <li>To view the Real Cars Detection</li>
  <p><code>python yolo_object_detection2.py</code></p>
</ol>
<ol start="5">
  <li>To view the Real Room Detection</li>
  <p><code>python yolo_object_detection3.py</code></p>
</ol>
<ol start="6">
  <li>To view the Real Walking Detection</li>
  <p><code>python yolo_object_detection4.py</code></p>
</ol>

## Graphical User Interface:

#### A Gaming Cars Detection
<img src="https://github.com/muhammadshiraz/yolo_object_detection/blob/master/doc/detector1.jpg">

#### A Real Cars Detection
<img src="https://github.com/muhammadshiraz/yolo_object_detection/blob/master/doc/detector2.jpg">

#### A Real Room Detection
<img src="https://github.com/muhammadshiraz/yolo_object_detection/blob/master/doc/detector3.jpg">

#### A Real Walking Detection
<img src="https://github.com/muhammadshiraz/yolo_object_detection/blob/master/doc/detector4.jpg">

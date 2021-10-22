<a  href="https://imgbb.com/"><img align="center" src="https://i.ibb.co/n68ztcX/t-l-charg.png" alt="t-l-charg" border="0"></a>

<h1>About</h1>
<p>Smart Dressing is an app based on yolov5 object detection algorithm that aims to detect clothing items.</p>

<h2>Getting Started </h2>

1. Install dependecies  
+ pip install -r requirements.txt

2. run the script 
+ python detect.py --source 0 --weights runs/train/yolo_clothing_det/weights/best.pt --conf 0.25 --name yolo_clothing_det
+ change the source parameter depending on the source needed image,video or webcam

3. Example

<a href="https://imgbb.com/"><img src="https://i.ibb.co/QYNFtdf/test.jpg" alt="test" border="0"></a>

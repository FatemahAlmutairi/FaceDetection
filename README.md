# Simple Face Detection

Face and object detection using YOLOv8. Works on images and live webcam.

## Run it

```bash
pip install opencv-python ultralytics jupyter
jupyter labOpen program.ipynb and run it. Press x to close the camera.

Files

program.ipynb - main code
yolov8n.pt - YOLO object detection
yolov8m-face.pt - YOLO face detection (from Akanametov)
demo*.jpg - test images
Models

Official YOLOv8 from Ultralytics
Face model: https://github.com/akanametov/yolo-face (thanks to Akanametov)
Notes

Runs on CPU (no GPU needed)
Nothing gets saved
Change 0 to 1 in VideoCapture() if camera doesn't work
Requirements

Python 3.8+
OpenCV
Ultralytics
Jupyter

Built while learning YOLO. Works fine.

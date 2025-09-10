<H1 align="center">
Vehicle Detection with DeepSORT and YOLO </H1>

## Steps to run Code

- Clone the repository
```
git clone https://github.com/aritrabag/ai_traffic_analyzer.git
```
- Goto the cloned folder.
```
cd YOLOv8-DeepSORT-Object-Tracking
```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect
```

- Downloading a Sample Video from the Google Drive
```
pip install gdown
gdown "https://drive.google.com/file/d/1N-tGT5mYAnSpgK8L_YokN0lw3ESp_sjf/view?usp=sharing"
```

  Run the code with mentioned command below:
- yolov8l object detection + Tracking + Vehicle Counting
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```

# AI-Robotics-Project
Object detection for robotic arms using YOLOv8
# AI-Robotics-Project

## Phase 1: Object Detection for Robotic Arm
- Uses YOLOv8 to detect cups/bottles
- Outputs coordinates for robotic control

```python
!pip install ultralytics
from ultralytics import YOLO
model = YOLO('yolov8n.pt')  # Auto-downloads model

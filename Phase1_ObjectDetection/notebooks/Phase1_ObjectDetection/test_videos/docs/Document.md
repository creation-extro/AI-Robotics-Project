# AI Robotic Object Detection

## How to Use
1. Run `notebooks/object_detection.ipynb` in Colab
2. It will detect objects in `test_videos/demo_objects.mp4`

## Results
- Detected: Cups, Bottles  
- Accuracy: 85%  
- FPS: 24

## What Worked Well
- Successfully detected cups/bottles  
- Compressed video from 130MB → 9MB  

## Challenges  
- Initially missed small objects  
- Fixed by adjusting confidence threshold to 0.7  


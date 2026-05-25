# AI-Enabled-Travel-Guide-in-Metro

AI-powered metro travel assistance system that uses YOLOv8 object detection to monitor passenger crowd levels, detect seat availability, and suggest less crowded metro compartments for a more comfortable journey.

## Features
- Real-time passenger detection
- Empty seat detection
- Crowd status monitoring
- Smart metro compartment analysis
- AI-based object detection using YOLOv8
- Video-based passenger tracking
- Comfortable coach recommendation system

## Technologies Used
- Python
- OpenCV
- YOLOv8
- NumPy
- Ultralytics

## Project Files
- metro_13.py
- yolov8n.pt
- Metro video dataset

## Installation

pip install ultralytics
pip install supervision
pip install opencv-python
pip install numpy

## Run Project

python metro_13.py

## Working Process
1. Load metro compartment video
2. Detect passengers using YOLOv8
3. Analyze crowd density
4. Detect empty seats
5. Display passenger count and coach status
6. Generate smart travel guidance

## Output
- Passenger count detection
- Empty seat availability
- Crowd status:
  - Comfortable
  - Moderate
  - Crowded
- Smart metro guidance display

## Future Enhancements
- Real-time CCTV integration
- Mobile application support
- Multi-coach analysis
- Live metro recommendations


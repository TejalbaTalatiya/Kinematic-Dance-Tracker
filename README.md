# Markerless Motion Capture & Kinematic Variance Evaluation Engine for Choreography
**Domain:** Advanced Computer Vision & Kinematic Tracking Systems

## Project Abstract
Repurposing trajectory tracking logic from space defense tracking systems, this project implements a high-precision, markerless motion-capture pipeline optimized for the commercial entertainment sector. Utilizing OpenCV video decoding arrays and MediaPipe's deep-learning pose estimation models, the system tracks 33 distinct multi-agent skeletal joints simultaneously. It calculates real-time Euclidean distance variance metrics relative to a dynamic group spatial center to measure choreographic synchronization down to the millisecond.

## Core Engineering Competencies Tested
* **Real-time Computer Vision Pipelines:** Processing sequential frame matrices in real-time.
* **Skeletal Coordinate Map Extraction:** Extracting 3D telemetry spatial matrices (`X, Y, Z`) without sensor equipment.
* **Trajectory Drift Analytics:** Setting tracking anchors over moving human targets across frame progressions.

## Setup & Execution
Launch the markerless computer vision array:
'''bash
python motion_capture.py
'''

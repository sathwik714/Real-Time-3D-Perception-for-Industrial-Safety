# Real-Time-3D-Perception-for-Industrial-Safety
🚀 Overview

This project presents a real-time 3D perception pipeline designed for safety-critical industrial environments such as construction sites, mining zones, and heavy-machinery operation areas.

The system combines YOLOv8 object detection, monocular depth estimation, and a Bird’s-Eye View (BEV) projection to create an end-to-end AI solution capable of:

Detecting workers, vehicles, and obstacles in real time

Estimating 3D distances using a single camera

Generating a top-down BEV visualization

Triggering threat alerts based on proximity

🎯 Key Features

✅ 1. Real-Time Object Detection (YOLOv8)

Detects workers, helmets, machinery, trucks, and other key industrial objects

Supports high-FPS inference on GPU and optimized CPU platforms

Lightweight and deployable on embedded hardware

✅ 2. Monocular Depth Estimation

Estimates distance of every object from the camera using a single RGB image

Uses a modern depth-estimation model such as SCDepthV3 / MiDaS

Helps convert 2D detections into 3D spatial awareness

✅ 3. Bird’s-Eye View (BEV) Projection

Produces a real-time top-down spatial map of the environment

Visualizes object positions, estimated distances, and danger zones

Helps operators understand nearby obstacles even with limited visibility

✅ 4. Threat Detection & Alerts

The system computes proximity thresholds and raises alerts for:

Worker too close to machine

Machine approaching obstacle

Restricted-zone violation

Sudden movement in danger radius

Alerts can be:

Displayed on screen

Logged

Sent to hardware buzzers or dashboards

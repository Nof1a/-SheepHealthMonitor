# Sheep Health Monitoring Platform

This project is a Sheep Health Monitoring Platform designed for sheep owners to monitor the health status of their sheep. The platform uses YOLOv9 for detecting various health conditions and provides a user-friendly interface for accessing this information.

## Features

- Detects and monitors various health conditions of sheep using YOLOv9.
- User-friendly web interface built with Flask.
- Easy to install and run.


## Files

- `app.py`: Main application file for running the Flask web server.
- `detect.py`: Script for detecting health conditions in sheep using YOLOv9.
- `requirements.txt`: List of required Python packages.

## Model Weights

The following model weights are used in this project:

- `best_yolov9_weights.pt`: YOLOv9 model weights for general detection.
- `best2.pt`: Secondary model weights for specific conditions.
- `healthy.pt`: Model weights for detecting healthy sheep.
- `teeth.pt`: Model weights for detecting teeth conditions in sheep.

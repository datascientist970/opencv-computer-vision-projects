# OpenCV Computer Vision Projects

Three small, focused **OpenCV** scripts: face detection in video, motion-based object detection, and perspective warping of a card image.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)

## Overview

## Origin

This project was originally developed inside the `Data-Science` projects collection and now lives in its own repository for easier discovery and use.

Each script is self-contained and demonstrates one classic computer-vision technique with plain OpenCV — no deep learning required.

## Projects

| Script | What it does |
|---|---|
| `face_detection.py` | Detects faces in a video stream with a Haar cascade (`CascadeClassifier`) and draws bounding boxes in real time |
| `motion_object_detection.py` | Detects moving objects by frame differencing → Gaussian blur → threshold → dilation → contours |
| `perspective_warp.py` | Bird's-eye view of a card: picks 4 corner points, computes the perspective transform and warps the image flat |

## Getting Started

```bash
git clone https://github.com/datascientist970/opencv-computer-vision-projects.git
cd opencv-computer-vision-projects
pip install -r requirements.txt
python face_detection.py
```

The scripts reference sample media (`walk.mp4`, `video/peoples.mp4`, `images/cards.jpg`, and a Haar cascade file `face.xml`) — media files are not included in this repository, so point the paths in each script at your own files. Press `q` to quit the video windows.

## Tech Stack

Python · OpenCV · NumPy

## Author

**Muhammad Dawood** — AI & Data Science Engineer
GitHub: https://github.com/datascientist970 · LinkedIn: https://www.linkedin.com/in/dawood406/
Mardan, Khyber Pakhtunkhwa, Pakistan

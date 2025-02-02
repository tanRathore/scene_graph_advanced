# Scene Graph Advanced Project

This project implements an end-to-end pipeline that:
- Extracts frames from an input video.
- Runs advanced object detection and ROI feature extraction using a pre-trained Faster R-CNN with FPN.
- Predicts relationships between objects via a modular relationship predictor.
- Constructs per-frame scene graphs and aggregates them into an overall scene graph.
- Uses a simple centroid tracker to link objects across frames.
## How to Run

1. Place your video file in the `data/` folder (named `input_video.mp4`).
2. Adjust the `BASE_DIR` in `run_pipeline.py` to your absolute project path.
3. Install dependencies with: pip install -r requirements.txt


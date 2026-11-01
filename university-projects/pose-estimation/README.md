# Pose estimation

Human pose estimation experiments from November 2024.

| File | What it is |
| --- | --- |
| `openpose.py` | OpenCV script running the OpenPose model on an image, video or webcam, drawing the detected skeleton |
| `simple-pose-coco.ipynb` | Training a SimplePose model on COCO keypoints with GluonCV and MXNet |

The OpenPose script needs the model weights file passed with `--proto` and
`--model`. Weights are not included.

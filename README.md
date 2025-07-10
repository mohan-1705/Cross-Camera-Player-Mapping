⚽ Cross-Camera Soccer Player Detection using YOLOv11
This project is a part of the AI/ML Internship Assignment focused on Task 1: Cross-Camera Player Mapping. The objective was to detect soccer players from two different camera views — a broadcast view and a tacticam view — using the YOLOv11 object detection model trained on a custom Roboflow Soccer Dataset.

📌 Objective
The main goal of this task was to:

Use YOLOv11 to detect soccer players in videos from two camera angles.

Train the model using a Roboflow dataset.

Apply the trained model to two real video files (broadcast.mp4 and tacticam.mp4).

Output annotated versions of the videos highlighting detected players.

🛠️ Tools & Libraries Used
YOLOv11 (via ultralytics)

Roboflow (custom dataset and API integration)

OpenCV (for video processing and annotation)

Google Colab / Local Runtime (VS Code) for development

gdown (for downloading videos and weights from Google Drive)

🚀 Setup Steps Followed
✅ 1. Environment Setup
Ensured Python 3.10+ and PyTorch GPU version installed.

Installed ultralytics, roboflow, opencv-python, and gdown.

✅ 2. Downloaded Model & Videos
Downloaded the trained YOLOv11 weights (best.pt) from Google Drive.

Downloaded two soccer match videos: broadcast.mp4 and tacticam.mp4.

✅ 3. Model Inference
Loaded the best.pt YOLOv11 model.

Ran predictions on each video frame-by-frame.

Annotated the detected players directly on the video frames.

✅ 4. Saved Annotated Outputs
Saved the annotated results as:

broadcast_output.mp4

tacticam_output.mp4

Each video showed bounding boxes around detected players, confirming that detection worked across both camera views.

📦 Files in the Project
soccer_task1_cross_camera_yolov11_*.ipynb: Main notebook used for running all steps.

broadcast.mp4: Input video from broadcast camera.

tacticam.mp4: Input video from tacticam camera.

broadcast_output.mp4: Output video with YOLOv11 detection annotations.

tacticam_output.mp4: Output video with YOLOv11 detection annotations.

best.pt: Trained YOLOv11 weights.

👨‍💻 Author
Ch. Mohan
LinkedIn
Email: chodabathulamohanarangaji@gmail.com


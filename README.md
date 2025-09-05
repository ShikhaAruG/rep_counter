🏋️ GymTracker – Rep Counter

A computer vision–based project that automatically counts exercise repetitions using Python, OpenCV, and Mediapipe.
This project was developed in a Jupyter Notebook (main.ipynb) for experimentation and testing.

🚀 Features

Real-time pose detection using Mediapipe Pose.

Counts exercise repetitions (like bicep curls, squats, push-ups, etc.).

Visual feedback with OpenCV video feed (rep counter and status displayed on screen).

Implemented entirely in a Jupyter Notebook for easy experimentation.

🛠️ Requirements

Make sure you have the following installed:

pip install opencv-python mediapipe jupyter

▶️ Usage

Clone this repository:

git clone https://github.com/ShikhaAruG/rep_counter.git
cd rep_counter


Start Jupyter Notebook:

jupyter notebook


Open main.ipynb and run the cells.

The webcam feed will open. Perform the exercise in front of the camera, and the rep counter will display in real-time.

📊 How It Works

Uses Mediapipe Pose to detect body landmarks.

Calculates angles (e.g., elbow, knee) to determine up and down positions.

Increments a counter when a full rep is completed.

Displays feedback overlay (reps, stage, etc.) using OpenCV.

📸 Example Output

Video feed with counter in the corner

Stage detection (e.g., up, down)

Repetition count updating in real-time

👩‍💻 Author
Developed by Shikha Gupta as part of a learning project in computer vision and human pose estimation.
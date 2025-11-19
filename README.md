🎥 Video Surveillance using Computer Vision

Project by Nouf Alenazi

📌 Overview

This project demonstrates a Video Surveillance System built using Computer Vision techniques.
The system processes video frames, applies object detection logic, and visualizes the output directly inside Google Colab.

It reflects hands-on experience in:
	•	Image processing
	•	Video analytics
	•	Computer vision pipelines
	•	Realtime frame handling
	•	Integration of OpenCV with Python & Colab

⸻

🛠️ Technologies Used
	•	Python
	•	OpenCV (cv2)
	•	NumPy
	•	Matplotlib
	•	PIL
	•	Google Colab environment
	•	Shell commands (git, sed, etc.)

⸻

📂 Project Files

/video-surveillance
│
├── videosurveillance.ipynb       # Main notebook
├── samples/                      # (Optional) Sample images/videos
├── results/                      # Output frames
└── README.md                     # Project documentation


⸻

💡 Features

✔ Frame-by-frame video processing
✔ Ability to integrate YOLO / Darknet (as shown in your code)
✔ Real-time visualization inside Colab
✔ Image preprocessing and enhancement
✔ Modular code structure for easy modification

⸻

🚀 How to Run the Project
	1.	Open the notebook in Google Colab.
	2.	Install dependencies (if needed):

!pip install opencv-python pillow matplotlib numpy


	3.	Upload your video file to Colab.
	4.	Run the notebook cells to start frame extraction & visualization.
	5.	Results will appear inline or inside the results folder.

⸻

🔧 YOLO / Darknet Integration

The notebook includes setup commands for Darknet to run YOLO-based detection:

!git clone https://github.com/AlexeyAB/darknet
%cd darknet
!sed -i 's/OPENCV=0/OPENCV=1/' Makefile
!sed -i 's/GPU=0/GPU=1/' Makefile
!sed -i 's/CUDNN=0/CUDNN=1/' Makefile
!sed -i 's/CUDNN_HALF=0/CUDNN_HALF=1/' Makefile
!sed -i 's/LIBSO=0/LIBSO=1/' Makefile

This step prepares the environment for running YOLO on your video stream.

⸻

📊 Skills Demonstrated

This project shows strong capability in:
	•	Computer Vision
	•	Python scripting
	•	Model integration (YOLO/Darknet)
	•	Data preprocessing
	•	Debugging & environment setup
	•	Working with GPU environments in Colab

Perfect to add to your GitHub portfolio for Data, AI, and CV-related roles.

⸻

👩‍💻 About the Developer

Nouf Alenazi
Data Analyst & Machine Learning Enthusiast
Skills: Python | SQL | Power BI | Computer Vision | Data Cleaning | Dashboard Design
LinkedIn: https://www.linkedin.com/in/nouf-alenazi-3a5750183/
Email: noufalenazi5@gmail.com

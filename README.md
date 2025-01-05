# Thief-Detection-System
A motion detection project using Python and OpenCV that alarms you when an unwanted visitor enters your monitored area. Perfect for testing your image processing skills and showcasing real-world computer vision applications.

![image](https://github.com/user-attachments/assets/a2b7dae9-d7b1-49eb-9869-ddd2ce013eed)


📹 How It Works

Live Video Feed: Captures live video from your webcam.

Reference Background Setup:

The first frame captured serves as the reference background image.

Motion Detection:

Each new frame is compared against the reference background using Background Subtraction (cv2.absdiff).

If significant pixel differences are detected, it indicates the presence of an intruder.

Alert Mechanism:

If an intruder is detected, the frame will display the text "UNSAFE" in red on the top right corner.

Live Feed Recording:

The video feed will be saved for evidence and review.

📦 Project Structure

main.py - Main script for running the motion detection algorithm.

data/ - Folder to store captured video feeds.

requirements.txt - Required Python libraries.

🚀 Technologies Used

Python

OpenCV

📊 Key Concepts Applied

Image Processing

Background Subtraction (cv2.absdiff)

Motion Detection

Live Video Capture and Storage

🏆 Why This Project Stands Out

Real-world security use case

Hands-on experience with OpenCV

Great for showcasing computer vision skills to recruiters

📧 Contact

For inquiries, feel free to reach out via GitHub.

✅ If you find this project interesting, don't forget to star the repository! 🌟


# image-resize-with-hand-gestures
A Python-based real-time image resizing tool using hand gestures with OpenCV and MediaPipe.

# 🤚 Hand Gesture-Based Image Resizing

A real-time computer vision project that enables users to resize images using only hand gestures. Built with Python, OpenCV, and MediaPipe, this system uses a webcam to detect and track finger movements to scale images dynamically — no mouse or keyboard required!

## 🚀 Features

- 📷 Real-time webcam input
- ✋ Hand tracking using MediaPipe
- 🔄 Dynamic image resizing based on finger distance
- 🖼️ Touchless and intuitive user experience
- 💾 Option to save resized image (customizable)
- 🖤 Lightweight, fast, and works on most systems

## 🛠️ Tech Stack

- **Python**
- **OpenCV** – image processing and webcam handling
- **MediaPipe** – hand gesture recognition
- **NumPy** – mathematical operations

## 📷 How It Works

1. OpenCV captures video feed from your webcam.
2. MediaPipe detects hand landmarks in the frame.
3. The system calculates the distance between the thumb and index finger.
4. This distance is mapped to a scaling factor.
5. The image resizes in real-time based on hand gesture distance.

For example:
- Moving fingers apart ➡️ Enlarges the image.
- Bringing fingers closer ➡️ Shrinks the image.

## 🔧 Installation

```bash
git clone https://github.com/ArchanaHublikar/image-resize-with-hand-gestures.git
cd hand-gesture-image-resizing
pip install -r requirements.txt

LICENSE
MIT © 2025 Archana Hublikar

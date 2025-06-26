# -Resize-the-Colored-Video-to-50-smaller-
PROJECT CATEGORY
# 🔄 Video Resizer to 50% 📏  
A Simple Python Script to Shrink Videos by Half  
**by Anurag Saini**

## 🚀 Overview

Want to reduce your video file size while maintaining decent quality? This script resizes any video to **50% of its original width and height** using OpenCV, making it perfect for web uploads, storage-saving, or faster processing in machine learning workflows.

Ideal for:
- Reducing file size  
- Optimizing for mobile/web playback  
- Preprocessing for ML pipelines

---

## 📌 Features

✅ Automatically reduces resolution to 50%  
✅ Supports `.mp4` and other popular formats  
✅ Keeps original video quality as much as possible  
✅ Easy to use and modify  
✅ Built with Python and OpenCV

---

## 🛠️ Requirements

Make sure you have the following installed:

- Python 3.x  
- OpenCV (`cv2`)  

To install OpenCV, run:

```bash
pip install opencv-python


📂 How to Use
🖥️ In Google Colab or Locally:
Upload or provide the path to your video.

Set the input_video_path and output_video_path.

Run the script — your resized video will be saved.

🔧 Example:
## 🧠 How It Works

- Opens the video file using OpenCV  
- Calculates 50% of the original frame width and height  
- Resizes each frame using `cv2.resize()`  
- Saves the resized video to a new file

---

## 📸 Visual Explanation

| Original Size | Resized (50%) |
|---------------|---------------|
| 1920x1080     | 960x540       |

---

## 📄 Code Snippet

```python
new_width = int(frame_width * 0.5)
new_height = int(frame_height * 0.5)
resized_frame = cv2.resize(frame, (new_width, new_height), interpolation=cv2.INTER_AREA)


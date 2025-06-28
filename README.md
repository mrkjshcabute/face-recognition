# 👨 Face Recognition

A face recognition system built with Python that identifies known individuals from a folder of stored images and labels unknown faces. This project was developed and tested using the **Spyder IDE**.

## ✨ Features

- ✅ Face detection and recognition using OpenCV and face-recognition libraries
- 🧾 Displays **name** and **confidence score** (e.g., 87.5%)
- ❓ Marks unrecognized faces as **"Unknown"**
- 🧠 Supports multiple images per person for better accuracy
- 🖥️ Built and tested in **Spyder (Anaconda Environment)**

## 🛠️ Built With

- Python
- OpenCV (`cv2`)
- NumPy
- Spyder IDE (Anaconda)

## ❓ How It Works

- The program scans a **folder of stored images**, where **each subfolder is named after a person**.
- When a new face is detected via webcam or a test image:
  - It compares the face with the stored ones.
  - If a match is found, it displays the **person's name** and the **confidence percentage**.
  - If the face does not match any stored images, it labels it as **"Unknown"**.

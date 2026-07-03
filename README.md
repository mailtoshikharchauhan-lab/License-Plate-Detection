# 🚗 License Plate Detection and Recognition using YOLOv8 + EasyOCR

A real-time Automatic License Plate Recognition (ALPR) system built using **YOLOv8** for license plate detection and **EasyOCR** for text recognition.

## Features

- Real-time license plate detection
- OCR using EasyOCR
- Automatic text correction
- License plate stabilization using majority voting
- Zoomed-in license plate overlay
- Confidence threshold filtering
- Saves annotated output video

---

## Project Structure

```
License-Plate-Detection/
│
├── easyocryoloLive.py
├── license_plate_best.pt
├── vehicle_video.mp4
├── output_with_licensev3.mp4
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/mailtoshikharchauhan-lab/License-Plate-Detection.git
cd License-Plate-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run

```bash
python easyocryoloLive.py
```

---

## Technologies Used

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- EasyOCR
- NumPy

---

## Output

The program generates an annotated output video showing:

- License plate detection
- OCR recognized text
- Zoomed-in license plate
- Stabilized license plate text

---

## Future Improvements

- Vehicle Tracking using DeepSORT
- Multiple OCR engines
- Super Resolution for blurry plates
- FPS Optimization
- Database Integration

---

## Author

Shikhar Chauhan

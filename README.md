# Driver Drowsiness Detection System  

A Machine Learning and Python-based project that detects driver drowsiness using **facial landmarks** and raises an alert when drowsiness is detected. The system helps in preventing accidents caused by fatigue during driving.  

---

## Features  
- ML-based **eye movement detection**  
- **Eye Aspect Ratio (EAR)** for drowsiness detection  
- **Real-time monitoring** with webcam  
- **Alarm alert** when eyes remain closed  
- Lightweight and efficient  

---

## Technologies Used  
- Python 3.7(only)  
- OpenCV  
- Dlib (68 facial landmark model)  
- Numpy  
- Imutils  

---

## Project Structure  

```bash
DriverDrowsinessSystem/
│
├── models/
│ └── shape_predictor_68_face_landmarks.dat   # Pre-trained ML model
│
├── Drowsiness_Detection.py   # Main Python script
├── music.wav # Dependencies
└── README.md # Documentation
```

---

## Getting Started


Follow these steps to run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/DriverDrowsinessSystem.git
cd DriverDrowsinessSystem
```

### 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Program

```bash
python drowsiness_detection.py
```

---

## Note

- Ensure your webcam is working before running the project.
- The models/shape_predictor_68_face_landmarks.dat file is required (download separately if not included).
- Replace music.wav with your preferred music/sound file for alerts.




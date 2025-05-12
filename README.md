# Driver-Assistant-System
**Technologies Used: Python, Machine Learning**
Data Analysis Designed and implemented a Driver Assistant System using Python and machine learning techniques. The system analyzes real-time data to provide safety recommendations and assist with navigation.

# Driver State Detection System 🚗💤

A real-time driver monitoring system to detect drowsiness, distraction, and gaze deviations using computer vision techniques.

## 🔍 Features
- Eye Aspect Ratio (EAR) tracking for drowsiness detection
- PERCLOS (Percentage of Eye Closure) calculation
- Gaze score to monitor eye focus direction
- Head pose estimation (yaw, pitch, roll)
- Audio alert system for fatigue or distraction
- Real-time face and eye keypoint visualization

## 🧰 Technologies & Libraries
- Python
- OpenCV
- dlib
- numpy
- pygame

## 🛠 Installation

### 1. Clone the Repository

bash
git clone https://github.com/your-username/driver-state-detection.git
cd driver-state-detection


**2. Install Required Libraries**
pip install -r requirements.txt

Required:
Download shape_predictor_68_face_landmarks.dat and place it in the predictor/ folder.

**3. Optional: Install pygame for audio alerts**
pip install pygame

**▶️ Usage**
python main.py

**🧪 How It Works**
Detects driver face using dlib
Tracks 68 facial landmarks
Calculates EAR and gaze score
Estimates head pose angles
Scores attention and triggers alerts if thresholds are crossed

**🤝 Contributions**
Pull requests are welcome. For significant changes, please open an issue first.

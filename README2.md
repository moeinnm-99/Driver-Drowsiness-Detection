# Driver Drowsiness Detection 🚗💤

A smart system that detects if the driver is becoming drowsy and alerts them immediately to prevent accidents. This project uses computer vision techniques to monitor eye closure, yawning, and body posture to identify signs of fatigue and warn the driver.

---

## 🛠️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/moeinnm-99/Driver-Drowsiness-Detection.git
````

### 2️⃣ Navigate to the Project Directory

```bash
cd Driver-Drowsiness-Detection
```

### 3️⃣ Run the Detection Script

Open a terminal inside the main folder and run:

* **Linux/macOS:**

```bash
python3 final-integration.py
```

* **Windows:**

```bash
python final-integration.py
```

### 4️⃣ Usage Instructions

* The program starts by taking pictures of your left and right eyes for calibration.
* After capturing, press the `Esc` key to start the detection phase.
* The system will then monitor:

  * Eye openness
  * Yawning
  * Head and body posture
* If signs of drowsiness are detected, the system will alert you and can open Google Maps to suggest rest stops.

---

## ⚙️ Features

* ✅ Eye State Detection (Open vs Closed)
* ✅ Yawn Detection
* ✅ Body Posture Analysis
* ✅ Real-time Drowsiness Alert
* ✅ Rest Area Recommendation via Google Maps

---

## 📷 Sample Output

### 👀 Open Eyes

<img src="https://github.com/SuperThinking/driver-drowsiness-detection/blob/master/working_images/OpenEyes.png" width="400"/>

### 😴 Closed Eyes

<img src="https://github.com/SuperThinking/driver-drowsiness-detection/blob/master/working_images/ClosedEyes.png" width="400"/>

### 🛑 Drowsiness Detected

<img src="https://github.com/SuperThinking/driver-drowsiness-detection/blob/master/working_images/Drowsy.png" width="400"/>

### 🧍 Drowsiness Based on Body Posture

<img src="https://github.com/SuperThinking/driver-drowsiness-detection/blob/master/working_images/DrowsyBodyPosture.png" width="400"/>

### 😮 Yawn Detection

<img src="https://github.com/SuperThinking/driver-drowsiness-detection/blob/master/working_images/YawnDetection.png" width="400"/>

### 😵 Drowsiness After Yawning

<img src="https://github.com/SuperThinking/driver-drowsiness-detection/blob/master/working_images/DrowsyAfterYawn.png" width="400"/>

---

## ⚠️ Important Notes

* The file `shape_predictor_68_face_landmarks.dat` is large (\~95MB). To avoid GitHub upload issues, consider using [Git Large File Storage (Git LFS)](https://git-lfs.github.com/).
* Make sure you have the required Python packages installed. You can install them with:

```bash
pip install -r requirements.txt
```

* Tested with Python 3.x

---

## 📬 Contributions

Contributions, issues, and feature requests are welcome! Feel free to:

* Fork the repository
* Create a new branch
* Commit your changes
* Open a pull request

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for checking out the project! Drive safely! 🚗💨

```

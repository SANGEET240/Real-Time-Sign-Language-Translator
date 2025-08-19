# ✋ Real-Time Sign language Translator  

## 📌 Project Overview  
This project aims to build a system that can detect **hand gestures** using a webcam and convert them into **text in real-time**.  
It is primarily designed to help bridge the communication gap between people with **hearing/speech impairments** and others.  

Currently, the project is **under development**. The first version includes **hand detection** using OpenCV & MediaPipe.  
Upcoming features include **gesture classification, text generation, GUI integration**, and **speech output**.  

---

## 👨‍💻 Team Members  
- Imran Ali Reza – 2211200010022  
- Sangeet Kumar Biswas – 2211200010045  
- Shyam Mondal – 2211200010034  
- Niladri Hati – 2211200010056  

**Mentor:** Dr. Ankita Dhar  
**College:** Sister Nivedita University  

---

## 🚀 Features (Planned & Implemented)  
- [x] Hand detection using OpenCV + MediaPipe  
- [ ] Gesture dataset collection (CSV format)  
- [ ] Gesture classification using ML (Scikit-learn / TensorFlow)  
- [ ] GUI with Tkinter for real-time display  
- [ ] Conversion of gestures into text  
- [ ] Optional speech output (gTTS / pyttsx3)  

---

## 🛠️ Technologies & Libraries  
- **Python 3.10**  
- **OpenCV** – Webcam access and image processing  
- **MediaPipe** – Hand tracking and landmark detection  
- **Tkinter** – GUI (to be added)  
- **Scikit-learn / TensorFlow** – Machine Learning model training  
- **NumPy, Pandas** – Data handling  

---

## 📂 Project Structure (so far)  
SignLanguageToText/  
│-- handmodule.py # Hand detection module  
│-- main.py # Main file (GUI + detection logic)  
│-- requirements.txt # Dependencies  
│-- README.md # Project documentation  

---

## ⚙️ Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/SANGEET240/Real-Time-sign-language-translator.git
   cd SignLanguageToText

2. **Create a virtual environment (recommended)**  
   ```bash
   "python -m venv venv"  
   "source venv/Scripts/activate"   # For Windows  

3. **Install dependencies**  
   ```bash
   "pip install -r requirements.txt"

4. **Run the project**
"python main.py"

📊 **Current Progress**
Hand detection works successfully using MediaPipe.
Initial GUI setup in Tkinter is in progress.
Next steps: gesture dataset collection & model training.

🔮 **Future Scope**
Support for full sign language vocabulary.
Two-way communication (text-to-speech & speech-to-sign).
Mobile or web-based deployment.

📖 **References**  
OpenCV Documentation - https://opencv.org/  
MediaPipe Documentation - https://developers.google.com/mediapipe  
Scikit-learn Documentation - https://scikit-learn.org/stable/  
Python Official Docs - https://docs.python.org/3/  

⚠️ **Note**
This project is still incomplete and under active development. Contributions from teammates are welcome. 🚀
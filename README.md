# Sign Language Recognition using OpenCV & CVZone  

This project is a **real-time Sign Language Recognition system** built using **OpenCV**, **CVZone**, and a pre-trained deep learning model.  
It detects hand gestures from a webcam feed, classifies them into **A–Z alphabets**, and provides both **visual** and **audio** feedback.  

---

## 🚀 Features  
- ✅ Real-time hand tracking using **CVZone HandTrackingModule**  
- ✅ Gesture classification using a **pre-trained Keras model**  
- ✅ Supports **A–Z alphabets recognition**  
- ✅ Converts predictions into **speech output** with `pyttsx3`  
- ✅ Easy to extend for custom datasets and gestures  

---

## 📂 Project Structure  

```
Sign-Language-Recognition/
│── Model1/
│   ├── keras_model.h5      # Pre-trained Keras model
│   ├── labels.txt          # Class labels (A–Z)
│
│── sign_language.py        # Main Python script
│── requirements.txt        # Python dependencies
│── README.md               # Project documentation
```

---

## 🛠️ Installation  

### 1. Clone the Repository  
```bash
git clone https://github.com/your-username/Sign-Language-Recognition.git
cd Sign-Language-Recognition
```

### 2. Install Dependencies  
Make sure you have **Python 3.8+** installed. Then run:  

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage  

Run the program with:  

```bash
python sign_language.py
```

### Controls:  
- The program will open your **webcam**.  
- Show a **hand gesture** (A–Z).  
- The model will:  
  - Display the recognized letter on screen  
  - Speak the recognized letter aloud  

---

## 🧠 Model Details  
- The project uses a **CNN-based model** trained on hand gesture images.  
- Model input size: `300x300` pixels.  
- Output: 26 classes (`A–Z`).  
- The `keras_model.h5` and `labels.txt` must be placed in the `Model1/` folder.  

---

## 📌 Requirements  
- Python 3.8+  
- OpenCV  
- CVZone  
- NumPy  
- TensorFlow / Keras  
- Pyttsx3  

---

## 📷 Demo  

| Gesture | Prediction | Output |
|---------|------------|--------|
| ✊       | A          | "A" (spoken) |
| ✌️       | V          | "V" (spoken) |
| 🖐️       | W          | "W" (spoken) |

---

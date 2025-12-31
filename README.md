# 📸 Marvellous Image Classifier

A **real-time image classification application** built using **MobileNetV2** (pre-trained on ImageNet).  
This project captures frames from your webcam, processes them, and overlays the predicted class label with confidence score directly on the video stream.

---

## ✨ Features
- Uses **MobileNetV2** (lightweight CNN model) with ImageNet weights.
- Real-time webcam feed classification.
- Displays **top-1 prediction** with confidence percentage.
- Simple and interactive interface (press `q` to quit).

---

## 🛠️ Tech Stack
- **Python 3.8+**
- **OpenCV** for video capture and display.
- **TensorFlow / Keras** for deep learning model.
- **NumPy** for numerical operations.

---

## 📂 Project Structure
```
Marvellous-Image-Classifier/
│
├── classifier.py        # Main script (contains MarvellousImageClassifier function)
├── README.md            # Documentation
└── requirements.txt     # Dependencies
```

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Marvellous-Image-Classifier.git
   cd Marvellous-Image-Classifier
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## 📦 Requirements
Add the following to `requirements.txt`:

```
tensorflow>=2.9.0
opencv-python
numpy
```

---

## ▶️ Usage

Run the script:
```bash
python classifier.py
```

- The webcam will start.
- Predictions will appear on the video stream.
- Press **`q`** to exit.

---

## 🖼️ Demo
When you run the program, you’ll see something like:

```
[INFO] Loading MobileNetV2 pre-trained model...
[INFO] Starting webcam...
```

And on the video stream:
```
Golden Retriever: 97.3%
```

---

## 🚀 Deployment on GitHub
1. Initialize Git in your project folder:
   ```bash
   git init
   ```
2. Add remote origin (if not already added):
   ```bash
   git remote set-url origin https://github.com/<your-username>/Marvellous-Image-Classifier.git
   ```
3. Commit and push:
   ```bash
   git add .
   git commit -m "Initial commit: Marvellous Image Classifier"
   git push -u origin main
   ```

---

## 👩‍💻 Author
**Samata Kadam**  




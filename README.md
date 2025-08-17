# Baggage-Threat-Detection-using-X-ray
 

🚨 Deep learning project for **automated threat detection** in X-ray baggage scans.  
Detects **guns, knives, pliers, scissors, and wrenches** using **YOLOv8**.  

---

## 📌 Project Overview  
- Trained on the **SIXray dataset** (17K+ X-ray images).  
- Compared **YOLOv8** and **YOLOv12** for detection performance.  
- ✅ **YOLOv8** achieved better accuracy (**mAP50 = 0.899**) and **17× faster inference** than YOLOv12, making it suitable for **real-time deployment**.  

---

## ⚙️ How to Run  

1. **Clone this repository**:      
   ```bash
   git clone https://github.com/ayamotawea/Baggage-Threat-Detection-using-X-ray.git
   cd Baggage-Threat-Detection-using-X-ray
   ```
2. **Install requirements**:
   ```bash
   pip install -r data/requirements.txt
   ```
3. **Run the Streamlit app**:
   ```bash
   streamlit run data/app.py
   ```
4. **Upload an X-ray image** → model predicts threats in real time.

## 📊 Sample Outputs


[output images folder](https://github.com/ayamotawea/Baggage-Threat-Detection-using-X-ray/blob/main/images)

## 📑 Dataset

- [SIXray Dataset on Kaggle](https://www.kaggle.com/datasets/khanhbtq99/sixray)


## 🛠 Tech Stack

- Python

- PyTorch · Ultralytics YOLOv8

- OpenCV

- Streamlit

## 📂 Repository Structure
```bash
├── data/                  # Streamlit deployment + model weights
│   ├── app.py
│   ├── best.pt
│   └── requirements.txt
├── images/                # Model output samples
├── baggage-threats-yolov8_final.ipynb   # Training notebook
├── docs/                  # Documentation + slides
└── README.md
```
## 📌 Future Work

- Add more threat categories (e.g., explosives, drones).

- Test robustness with out-of-distribution datasets.

- Optimize for edge-device deployment.


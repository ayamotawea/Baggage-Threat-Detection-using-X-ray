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

https://github.com/ayamotawea/Baggage-Threat-Detection-using-X-ray/blob/main/images

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

<img width="871" height="492" alt="1" src="https://github.com/user-attachments/assets/60fdf8a1-4d0e-46cc-9ebf-0640e2700eeb" />
<img width="871" height="492" alt="2" src="https://github.com/user-attachments/assets/98b1db81-532e-4ea1-beda-bf8cabb5b4b7" />
<img width="868" height="490" alt="3" src="https://github.com/user-attachments/assets/366df88f-70f2-4525-94c7-31d369c98660" />
<img width="872" height="489" alt="4" src="https://github.com/user-attachments/assets/b1a75d05-61c6-40eb-81c2-29a61ab58cad" />
<img width="870" height="493" alt="5" src="https://github.com/user-attachments/assets/8a306277-b321-4b32-b268-989f85daedac" />
<img width="868" height="486" alt="6" src="https://github.com/user-attachments/assets/936b2ed9-d459-49f9-9353-b036727e6eac" />
<img width="869" height="490" alt="7" src="https://github.com/user-attachments/assets/a7988d3d-3d29-4b73-b993-1834398e041d" />=
<img width="869" height="491" alt="8" src="https://github.com/user-attachments/assets/499b057e-41ed-45b3-bc04-1cb4f5c68ff7" />
<img width="870" height="490" alt="9" src="https://github.com/user-attachments/assets/70647b79-7e44-4c79-98b5-a133b3736eef" />
<img width="870" height="490" alt="10" src="https://github.com/user-attachments/assets/196138d8-43d9-4cdf-b737-5ca70bdc5df1" />
<img width="874" height="490" alt="11" src="https://github.com/user-attachments/assets/47c3fcfa-ac4a-4e8f-bb35-f61901b561e0" />
<img width="867" height="491" alt="12" src="https://github.com/user-attachments/assets/ee312756-149f-4dbe-9a90-2cee3ee94154" />
<img width="873" height="490" alt="13" src="https://github.com/user-attachments/assets/0f070800-9fc7-4076-be56-23272e5599f2" />
<img width="873" height="492" alt="14" src="https://github.com/user-attachments/assets/8e8fdaa6-626c-4ba3-8ee7-8f1004f7940f" />
<img width="871" height="488" alt="15" src="https://github.com/user-attachments/assets/9ec93fe9-a889-4808-b0ff-84359bcf3b2f" />
<img width="872" height="491" alt="18" src="https://github.com/user-attachments/assets/226dc625-bee0-4422-a839-58f10f726f51" />
<img width="873" height="490" alt="119" src="https://github.com/user-attachments/assets/d3cd3c38-0f5f-4b31-94d1-dcbd56f57d85" />
<img width="870" height="488" alt="19" src="https://github.com/user-attachments/assets/5ba1fe24-a850-4f14-927c-b17a5f14720f" />
<img width="871" height="490" alt="20" src="https://github.com/user-attachments/assets/ccf95acb-cd4a-4e11-9f86-94355f8d5537" />
<img width="870" height="490" alt="21" src="https://github.com/user-attachments/assets/173bd86d-8431-4e10-9058-ed35fe341001" />























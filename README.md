# ♻️ EcoSortAI – Smart Waste Classification & Recycling Guide

EcoSortAI is an AI-powered waste classification system that uses **Deep Learning** (CNN) to automatically identify different types of waste from images and provide **detailed recycling & disposal guidance**.  

The project includes:
- ✅ A trained **TensorFlow/Keras model**  
- ✅ An interactive **Tkinter desktop GUI**  
- ✅ A **Streamlit Web App** for deployment  
- ✅ Automatic **PDF report generation** with recycling details  

---

## 📸 Demo

### 🔹 Streamlit Web App
![Streamlit Demo](assets/streamlit_demo.png)

### 🔹 Desktop GUI
![GUI Demo](assets/gui_demo.png)

---

## 🚀 Features

- 🖼 **Upload waste image** → Get instant classification  
- 📊 **Confidence distribution chart** for model predictions  
- 📜 **Detailed recycling & environmental info**:
  - Hazard level (⚠️ Toxic / ✅ Safe)
  - Decomposition time
  - Carbon footprint reduction
  - Landfill reduction stats
  - Eco-friendly disposal tips
- 💾 **Downloadable PDF Report** for each prediction  
- 🌍 Designed for **real-world waste management** applications  

---

## 📂 Dataset

The dataset was split into **train (80%)**, **validation (10%)**, and **test (10%)**, and balanced across 12 classes:

- 🪫 Battery  
- 🌱 Biological  
- 🟤 Brown Glass  
- 📦 Cardboard  
- 👕 Clothes  
- 🟢 Green Glass  
- ⚙️ Metal  
- 📄 Paper  
- 🍼 Plastic  
- 👟 Shoes  
- 🗑 Trash  
- ⚪ White Glass  

---

## 🏗️ Tech Stack

- **Deep Learning** → TensorFlow / Keras  
- **GUI** → Tkinter  
- **Web Deployment** → Streamlit  
- **PDF Reports** → ReportLab  
- **Data Handling** → Pandas, NumPy, Matplotlib  

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/EcoSortAI.git
cd EcoSortAI


Install dependencies:

pip install -r requirements.txt


▶️ Usage
🔹 Run Desktop GUI
python GUI.py

🔹 Run Streamlit Web App
streamlit run app.py

📊 Results

✅ Final Model Accuracy: ~92%

✅ Smooth accuracy/loss curves (no overfitting/underfitting)

✅ Works on both dataset & real-world images

🌍 Real-World Impact

EcoSortAI can be deployed in:

🏙 Smart cities for automated waste sorting

🏫 Schools & colleges for awareness

🏭 Recycling plants for efficient operations

🏡 Households for eco-friendly waste management

📜 License

MIT License © 2025 Rushikesh Kadam

🙌 Acknowledgements

TensorFlow Team

Streamlit Community

Open-source waste classification datasets


---

✨ You can also create an **`assets/` folder** inside your repo and put **screenshots of your GUI & Streamlit app** (replace the `assets/gui_demo.png` and `assets/streamlit_demo.png` with your actual image names).  

Would you like me to also give you a **ready `requirements.txt`** for GitHub deployment so you don’t face errors on Streamlit Cloud?

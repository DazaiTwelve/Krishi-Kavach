# 🌾 Krishi Kawach — AI-Powered Crop Disease Detection & Rainfall Forecasting

**Krishi Kawach** is an intelligent, AI-driven web platform designed to empower farmers with real-time agricultural insights. It enables users to detect crop diseases from images using deep learning and forecasts rainfall trends with the help of advanced ML models. The solution combines:

- 🧠 **AI-powered image classification** supporting over **40 crop diseases**
- ⚡ **Rainfall prediction interface** built with interactive **React.js**
- 🎯 **Clean static landing page** for seamless user navigation

From diagnosis to decision-making — Krishi Kawach is your digital farming assistant in the cloud.

🔗 **Live Demo:** [https://krishi-kavach.vercel.app](https://krishi-kavach.vercel.app)  
🎥 **Demo Video:** [Watch here](https://youtu.be/9bUOMbTX45g)

---

## ⚙️ Setup Instructions

### 1. Backend (Flask API)
```bash
cd "CropDisease prediction"/backend
python -m venv venv
venv\Scripts\activate     # On Windows
pip install -r requirements.txt
python app.py
```
### 2. Frontend (Rainfall - React App)
```bash
cd "RainFall Prediction/React/my-react"
npm install
npm run dev
```
### 3. Static Mainpage
```bash
Just open Mainpage/index.html in your browser,
or deploy via Vercel, Firebase, or Netlify.
```
## 📁 Project Structure
```bash
CropDisease prediction/
│
├── backend/                  # Flask backend + ML APIs
│   ├── api/                  # API scripts and model code
│   ├── Dockerfile            # Container setup for deployment
│   ├── requirements.txt      # Python dependencies
│   └── vercel.json           # Vercel deployment config
│
├── frontend/                 # React frontend (if applicable)
│   └── pages/                # Pages for deployment
│
├── Mainpage/                 # Static landing page for users
│   ├── index.html            # Homepage HTML
│   ├── style.css             # Styling
│   ├── script.js             # Interactivity logic
│   ├── logo/                 # Logo images
│   ├── hs/, hs-fs/, hubfs/   # Asset directories
│   └── robots.txt            # SEO handling
│
├── RainFall Prediction/      # Rainfall prediction module
│   └── React/my-react/       # React frontend for rainfall
│       └── rainfall/         # Rainfall model logic
└── .gitignore
```
## 🚀 Features

- **🌿 Crop Disease Detection**  
  Upload leaf images and get instant **AI-based disease classification** with treatment suggestions.

- **🌧️ Rainfall Forecasting**  
  Predict **rainfall trends** using historical weather datasets and ML models.

- **🖥️ Landing Page**  
  Clean, responsive, **static homepage** with access to key features.

- **🧩 Modular Design**  
  Separate logic for **backend APIs**, **ML models**, static pages, and rainfall tools.

- **🌐 Live Deployment**  
  Hosted on **Vercel**, ready for public access and feedback.

---

## 👨‍💻 Contributors

- Rudra Verma  
- Sameer Shukla
- Aryan Bhardwaj  
- Himanshu Gupta  
- Sumit Parashar

---

## 📄 License

This project is licensed under the **MIT License**.  
You're free to use, modify, and distribute.

---

## 🙏 Acknowledgements

- 🌱 **PlantVillage Dataset**  
- 📚 **TensorFlow & Flask Documentation**  
- 🚀 **Vercel** for free deployment

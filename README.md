# 🌾 Krishi Kawach — AI-Powered Plant Disease Detection & Farmer Support Platform

**Krishi Kawach** (translated as "Crop Shield") is an AI-driven solution designed to empower farmers with rapid disease diagnosis, actionable insights, and an integrated agri-marketplace.

---
## 🎥 Demo Video

Watch the full working demo of **Krishi Kawach** below:

👉 [Click to watch on YouTube](https://youtu.be/9bUOMbTX45g)

[![Watch the video](https://img.youtube.com/vi/9bUOMbTX45g/0.jpg)](https://youtu.be/9bUOMbTX45g)


## 🚀 Project Structure

```

├── AI/
│   ├── Test\_plant\_disease.ipynb      # Notebook to test prediction pipeline
│   ├── train\_crops\_disease.ipynb     # Notebook to train the plant disease classifier
│   ├── check\_model\_file.py           # Model integrity checker
│   ├── app.py / main.py              # Flask backend entry points
│   ├── result.html / index.html      # Output & frontend test pages
│   ├── training\_hist.json            # Model training logs
│   └── updated\_index.html            # Enhanced HTML output
│
├── Frontend/
│   ├── MainPage/
│   │   ├── index.html                # Landing page for the platform
│   │   ├── script.js                 # Core JS for UI interaction
│   │   ├── style.css                 # Styling for the main UI
│   │   ├── robots.txt                # SEO/Robots setup
│   │   └── Home.zip                  # Archived source for main page
│   │
│   └── RainFall/
│       ├── src/                      # React source (future rainfall dashboard)
│       ├── Backend.py               # Python backend logic for rainfall analytics
│       ├── vite.config.js           # Vite config for dev server
│       ├── package.json             # Project dependencies
│       ├── eslint.config.js         # Linting config
│       └── index.html               # HTML entry point
│
├── SIH2024\_IDEA\_Presentation.pdf     # Official SIH idea pitch deck
├── LICENSE                           # Open-source license
├── .gitignore                        # Git exclusion rules
└── README.md                         # You're reading this 😉

````

---

## 🧠 AI Capabilities

- **Plant Disease Detection** using image-based CNNs
- Trained with real agricultural datasets from Kaggle
- Flask backend to process predictions and return results
- JSON logs of model training for transparency and reproducibility

---

## 🌐 Frontend Features

- Fully responsive landing page using **HTML/CSS/JS**
- **RainFall** dashboard (React + Vite) for real-time rainfall & advisory system (WIP)
- Integrated agri-marketplace and multilingual farmer support (planned)

---

## 🔥 How to Run

### 🧠 AI Backend

```bash
cd AI
pip install -r requirements.txt  # Add one if it's missing
python app.py  # or use main.py if that's your entrypoint
````

### 🌐 Frontend - MainPage

```bash
cd Frontend/MainPage
# Simply open index.html in your browser
```

### ⚛️ Frontend - RainFall (React)

```bash
cd Frontend/RainFall
npm install
npm run dev
```

> ⚙️ Ensure Vite is installed and working:
>
> ```bash
> npm install -g vite
> ```

---

## 📊 Presentation

The official Smart India Hackathon 2024 proposal and pitch deck is available in the root directory:

`SIH2024_IDEA_Presentation.pdf`

---

## 👨‍🌾 Team Hisenburg

* Rudra Verma
* Aryan Bhardwaj
* Himanshu Gupta
* Sumit Parashar
* Sameer Shukla

---

## ⚖️ License

**MIT License** — feel free to contribute, adapt, or deploy for the betterment of agriculture.

---

> *“Empowering Bharat’s backbone—our farmers—with the power of artificial intelligence.”*

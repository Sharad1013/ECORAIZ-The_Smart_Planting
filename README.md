
# 🌿 EcoRaiz: The Smart Planting System

**EcoRaiz** is an intelligent planting system designed to help transform dry, barren land into thriving green forests. By combining image processing and environmental analysis, it identifies the best zones for planting and recommends tree species based on sustainability, soil condition, and climate.

---

## 📸 How It Works

1. **Upload Land Image**  
   User uploads a top-view image of the plot.

2. **Automatic Plot Division**  
   EcoRaiz divides the image into smaller sub-plots for detailed analysis.

3. **Environmental Data Input**  
   For each sub-plot, the user provides:
   - 🌡️ Temperature  
   - 💧 Humidity  
   - ⚗️ Soil pH  
   - 🌱 Soil Moisture  

4. **Analysis & Tree Suggestion**  
   The system:
   - Analyzes sub-plots
   - Ranks suitable planting zones
   - Suggests long-lifespan trees (20–50+ years)

5. **Visual Output**  
   Outputs a visually ranked overlay on the plot with planting suggestions.

---

## ⚙️ Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js (Express)
- **Image Processing**: Python (OpenCV, PIL, NumPy)
- **Database**: MongoDB (or your preferred storage)
- **Deployment**: Render / Vercel / Railway *(based on your choice)*

---

## 🚀 Setup Instructions

1. **Clone the Repo**
   ```bash
   git clone https://github.com/SuryaNarayananDev/ECORAIZ-The_Smart_Planting.git
   cd ECORAIZ-The_Smart_Planting
   ```

2. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

3. **Backend Setup**
   ```bash
   cd backend
   npm install
   npm run start
   ```

4. **Python (Image Processing) Setup**
   ```bash
   cd image-processing
   pip install -r requirements.txt
   python app.py
   ```

> Ensure all services (frontend, backend, and Python server) are running concurrently.

---

## 🛠️ Tasks & Issues

### ✅ Core Modules (MVP)
- [x] Image upload and preview
- [x] Auto-subdivision of image
- [x] Manual input of environmental values
- [x] Tree recommendation logic
- [x] Visual ranking output

### 📌 To-Do (Raise as GitHub Issues)
- [ ] Integrate ML for tree prediction
- [ ] Improve UI/UX of form and map
- [ ] Display tree info dynamically
- [ ] Add login/auth (optional)
- [ ] Add mobile responsiveness

---

## 🏷 GitHub Labels

We use labels to manage contributions:

| Label Name           | Purpose                                      |
|----------------------|----------------------------------------------|
| `good first issue`   | Beginner-friendly tasks                      |
| `feature`            | New functionality/features                   |
| `bug`                | Unexpected behavior/fix                      |
| `enhancement`        | UI/UX or performance improvements            |
| `help wanted`        | Needs more eyes or collaboration             |
| `documentation`      | Related to README, setup, or guides          |
| `question`           | Open-ended or usage queries                  |
| `design`             | UI or graphic related tasks                  |

---

## 🤝 Contributing

We welcome contributions from:

- 👨‍💻 Developers (JS, Python, ML)
- 🧪 Environmental Scientists
- 🎨 Designers
- 🌱 Sustainability Enthusiasts

### 📌 Steps to Contribute:
1. Fork the repository
2. Create your feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add feature"`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🌍 Mission

EcoRaiz is dedicated to data-driven reforestation. Our vision is to empower users to convert underutilized land into flourishing green zones with long-lasting ecological impact.

> **“Plant data, grow forests.” 🌱**

---

## 🔗 Links

- 🔗 [Live Demo (Coming Soon)](#)
- 📫 Contact: suryavignesh6238@gmail.com
- 🌐 Portfolio: [suryanarayanans.netlify.app](https://suryanarayanans.netlify.app)
- 🐙 GitHub: [@SuryaNarayananDev](https://github.com/SuryaNarayananDev)

# 🥗 Smart Diet Recommendation System

An **AI-powered Diet Recommendation System** that suggests personalized food recipes based on **nutritional requirements** and **ingredient preferences**.  
Built using **Machine Learning (KNN)**, **FastAPI** for backend, and **Streamlit** for an interactive frontend.

---

## 🚀 Features

- ✅ Personalized diet recommendations  
- ✅ Nutrition-based filtering (Calories, Fat, Protein, etc.)  
- ✅ Ingredient-based recipe search  
- ✅ Machine Learning powered (KNN + Cosine Similarity)  
- ✅ Interactive Streamlit UI  
- ✅ FastAPI backend for scalable predictions  
- ✅ Fallback recipes when API is unavailable  
- ✅ Modular & production-ready code structure  

---

## 🧠 Tech Stack

### 📊 Machine Learning
- Python  
- Scikit-learn (KNN, StandardScaler)  
- Pandas, NumPy  

### 🌐 Backend
- FastAPI  
- Uvicorn  

### 🎨 Frontend
- Streamlit  

### 📁 Dataset
- Recipe & nutrition dataset (CSV)  
- Nutritional attributes:
  - Calories
  - Fat Content
  - Saturated Fat
  - Cholesterol
  - Sodium
  - Carbohydrates
  - Fiber
  - Sugar
  - Protein

---

## 🏗️ Project Structure

```
Smart-Diet-Recommendation-System/
│
├── Data/
│   └── dataset.csv
│
├── FastAPI_Backend/
│   ├── main.py
│   ├── model.py
│   └── requirements.txt
│
├── Streamlit_Frontend/
│   ├── pages/
│   ├── ImageFinder/
│   ├── Generate_Recommendations.py
│   ├── Hello.py
│   └── requirements.txt
│
├── Food_Recommendation_System.ipynb
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Smart-Diet-Recommendation-System.git
cd Smart-Diet-Recommendation-System
```

---

### 2️⃣ Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # Linux/Mac
```

---

### 3️⃣ Install Dependencies

#### Backend
```bash
cd FastAPI_Backend
pip install -r requirements.txt
```

#### Frontend
```bash
cd ../Streamlit_Frontend
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### 🔹 Start FastAPI Backend
```bash
cd FastAPI_Backend
uvicorn main:app --reload
```

Backend runs at:
```
http://127.0.0.1:8000
```

---

### 🔹 Start Streamlit Frontend
```bash
cd Streamlit_Frontend
streamlit run Hello.py
```

Frontend runs at:
```
http://localhost:8501
```

---

## 🧪 Example Input

- Calories: 500  
- Protein: 30g  
- Fat: 25g  
- Ingredients: chicken, rice, broccoli  

➡️ Output: Healthy personalized recipe recommendations.

---

## 📊 Machine Learning Approach

- Algorithm: K-Nearest Neighbors (KNN)  
- Similarity Metric: Cosine Similarity  
- Preprocessing: Standard Scaling  
- Recommendation Type: Content-Based Filtering  

---

## 🧩 Use Cases

- 🏋️ Fitness & diet planning  
- 🧑‍⚕️ Nutrition recommendation  
- 🍽️ Personalized meal planning  
- 🎓 Academic & final year projects  

---

## 📌 Future Enhancements

- User profiles & history  
- Mobile-friendly UI  
- Cloud deployment  
- Hybrid recommendation system  
- Recipe image generation  
- Weekly meal planner  

---

## 👨‍🎓 Academic Use

Suitable for:
- Final Year B.Tech / B.E CSE Projects  
- Machine Learning Mini Projects  
- Data Science Portfolios  

---

## 📜 License

Educational use only. Free to modify and enhance.

---

⭐ If you like this project, give it a star!

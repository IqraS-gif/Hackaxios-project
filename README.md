<div align="center">
  <h1 style="font-family: 'Poppins', sans-serif; font-size: 56px; font-weight: 800; letter-spacing: -1.5px; margin-bottom: 10px; background: linear-gradient(to right, #6a11cb, #2575fc); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">
    🚀 Founders Fuel: The AI Co-Pilot for the Next Generation of Startups
  </h1>
  
  <p style="font-family: 'Poppins', sans-serif; font-size: 20px; font-weight: 500; color: #555; margin-top: 0;">
    From Idea to Investment — Smart Analysis for Founders & Investors
  </p>
    <a href="https://founder-s-fuel-final-code-1y38.vercel.app/" target="_blank">
      🔗 Visit The Website
    </a><br>
    <a href="https://youtu.be/ORUnEhAQxaE" target="_blank">
      🎥See The Demo Video
    </a>
</div>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

---

## 🌟 Overview

**Founders Fuel** bridges the gap between ambitious founders and venture capital.
Using advanced **RAG**, **LLMs**, and **Machine Learning**, this platform acts as a 24/7 intelligent consultant.

From pitch deck roasting to investor matching and startup validation — Founders Fuel has you covered.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/94e017ad-cf0c-4e9e-860b-3064256a387b" width="800" height="800" />
</p>

---

## ✨ Key Features

| Feature                         | Description                                                                                                                                                   |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **📊 AI Pitch Deck Analyzer**   | Upload PDF decks and receive deep analysis from **4 unique VC personas** with scoring on clarity, market, product, and fundraising strength.                  |
| **🤝 Smart Investor Matching**  | Match with the right investors based on sector, stage, geography, and thesis — with actionable outreach insights.                                             |
| **🧠 7-Domain Idea Evaluation** | A structured RAG-powered framework analyzing feasibility, market size, competitors, execution difficulty, defensibility, monetization, and user pain.         |
| **💬 RAG Chatbot (Standalone)** | A fully separate interactive chatbot for market research, competitor insights, idea refinement, and evidence-backed recommendations. Runs as a Streamlit app. |
| **🔮 Success Predictor**        | ML model with SHAP explainability to estimate your fundraising success probability and show why the model predicts that outcome.                              |

---
## 🧠 What Can People Use **Founders Fuel** For?

**Founders Fuel** is an AI-powered startup intelligence platform that simplifies, accelerates, and de-risks the hardest parts of building and investing in startups. It replaces fragmented tools, guesswork, and subjective opinions with **data-backed, explainable insights**—available 24/7.

---

## 👩‍💻 For Founders: Build Smarter, Pitch Better, Raise Faster

### 🚀 Turn Raw Ideas into Investor-Ready Startups

* Validate ideas **before** spending months building them
* Understand feasibility, defensibility, and monetization clearly
* Avoid common startup blind spots early

### 📊 Improve Pitch Decks Without Costly Advisors

* Get **brutally honest feedback** from multiple VC personas
* Identify weak slides, unclear narratives, and missing metrics
* Receive structured scores instead of vague opinions

### 🤝 Find the *Right* Investors (Not Just Any Investor)

* Match with investors aligned to your **sector, stage, geography, and thesis**
* Save time by avoiding cold outreach to misaligned VCs
* Get **actionable outreach insights**, not just names

### 🔮 Predict Fundraising Outcomes (and Why)

* Estimate fundraising success probability using ML
* See **why** your startup scores high or low using SHAP explainability
* Make informed improvements instead of guessing

### 💬 Research Faster With Evidence-Backed AI

* Ask market, competitor, or strategy questions
* Get grounded answers backed by retrieved data (RAG)
* Replace hours of Google, reports, and spreadsheets

---

## 💼 For Investors: Evaluate Faster, Fairer, and at Scale

### 🧠 Standardize Startup Evaluation

* Analyze decks using consistent, multi-dimensional frameworks
* Reduce bias from gut feeling or presentation polish
* Compare startups on **real fundamentals**

### ⏱️ Save Time on Deal Screening

* Instantly surface strengths, risks, and red flags
* Focus human time only on high-potential deals
* Scale analysis without increasing analyst headcount

### 📈 Data-Driven Investment Decisions

* Use ML-backed predictions instead of intuition alone
* Understand key drivers behind startup success or failure
* Improve portfolio-level decision quality

---

## 🔐 How It Makes Tasks Safer & More Reliable

* **Explainable AI (SHAP)** → No black-box predictions
* **RAG-based insights** → Reduced hallucinations, evidence-backed answers
* **Structured real life data** → Trained on real world data of **3 lakh+ startups and 3k+ global investors**. 
* **Persona-based analysis** → Multiple perspectives, not single-point bias

---
## 🔁 Traditional Approach vs **Founders Fuel**

| **Traditional Approach** | **With Founders Fuel** |
|--------------------------|------------------------|
| **Gut-driven, subjective pitch feedback** | **Multi-persona VC analysis (Mentor, Analyst, Strategist, Devil’s Advocate)** |
| **Opaque decisions with no clear reasoning** | **Explainable AI (SHAP) showing exactly what helped or hurt** |
| **Generic, one-size-fits-all advice** | **Startup-specific, instance-level insights** |
| **Cold investor outreach with low response rates** | **Smart investor matching by stage, sector, geography, thesis** |
| **Manual market & competitor research** | **RAG-powered, evidence-backed research chatbot** |
| **Black-box ML predictions** | **Interpretable ML with transparent success drivers** |
| **Expensive consultants & accelerators** | **24/7 AI startup co-pilot** |
| **Founder bias & network dependency** | **Democratized, unbiased startup evaluation** |


---

## 🛠️ Tech Stack

### **Frontend**

- React (Vite)
- Styled Components
- Recharts

### **Backend**

- Python
- FastAPI
- Google Gemini API
- HuggingFace Transformers (BERT, NER, Sentiment)
- SQLite
- Scikit-Learn + SHAP

### **RAG Module**

- Streamlit
- Pinecone
- Sentence Transformers
- PDF/Text ingestion

---

## 📂 Project Structure

```
founder-sfuel/
├── founders-fuel-ui/          # React Client
│   ├── src/
│   │   ├── components/        # UI Components
│   │   ├── pages/             # App Screens (CoPilot, Results)
│   │   └── api/               # Axios Interceptors
│   └── package.json
│
├── vc-copilot-backend/        # FastAPI Server
│   ├── app/
│   │   ├── core/              # ML & Model Config
│   │   ├── services/          # Matching, Pitch Processing
│   │   └── api/               # FastAPI Routes
│   ├── main.py
│   ├── requirements.txt
│   └── pitchmodel.pkl
│
└── finalcodes/                # Standalone Tools
    └── ragfinalone.py         # Streamlit RAG Chatbot
```

---

# 🚀 Project Setup Guide

## 🔐 Environment Variables (Required)

Create a `.env` file in `vc-copilot-backend/`:

```
GEMINI_API_KEY=

SERPAPI_API_KEY=

PINECONE_API_KEY=

```

## 🖥️ Frontend Setup

```
cd founders-fuel-ui
npm install
npm run dev
```

---

## ⚙️ Backend Setup (FastAPI)

```
cd vc-copilot-backend
uvicorn main:app --reload --port 8000
```

---

## 🧠 RAG Chatbot Setup (Standalone)

```
cd finalcodes
streamlit run ragfinalone.py
```

---

<div align="center">

Made with ❤️ by the **Team Iqraa**

</div>

---

# 🔍 InsightFlow – AI-Powered Media Analytics Platform

**Author:** Gitika Poudel  
**Student ID:** NPI000211  
**Supervisor:** Mr. Prem Prasad Shrestha  
**Programme:** BSc Information Technology  
**Institution:** Asia Pacific University of Technology & Innovation (APU)  
**Date:** December 2024  

---

## 📌 Project Overview

InsightFlow is an **AI‑powered media analytics platform** designed to combat **information overload** in digital environments. It automates content analysis and delivers multi‑dimensional insights—sentiment, bias, topics, and trends—through an intuitive dashboard.

The system employs a **hybrid AI‑custom algorithm approach**, leveraging **Natural Language Processing (NLP)** and **machine learning** to achieve high accuracy while remaining accessible and cost‑effective for researchers, journalists, and business professionals.

> **Sustainable Development Goal 9 (Industry, Innovation, and Infrastructure)** – Democratising access to advanced analytics and fostering innovation in information processing.

---

## 🎯 Project Objectives

| # | Objective | Target |
|---|-----------|--------|
| 1 | **Scalable Architecture** | Process 100+ articles concurrently, <2 sec/article |
| 2 | **High‑Accuracy Analysis** | Sentiment ≥85%, Topic extraction ≥80% precision |
| 3 | **Intuitive User Interface** | System Usability Scale (SUS) score ≥75 |
| 4 | **Cost‑Effective Operation** | <10% cost of enterprise solutions |

---

## ✨ Key Features

✅ **User Authentication** – Secure JWT‑based registration / login  
✅ **Multi‑dimensional Content Analysis**  
 • Sentiment scoring (–1 to +1) with confidence  
 • Bias detection (0‑100% scale)  
 • Topic extraction & entity recognition  
 • Reading time & word count estimation  
✅ **Interactive Dashboard** – Real‑time statistics, charts, recent activity  
✅ **Analysis History** – Browse, search, and review past analyses  
✅ **Sample Library** – Pre‑loaded articles for instant testing  
✅ **Export Reports** – Simulated PDF/JSON export  
✅ **Responsive Design** – Works on desktop, tablet, and mobile  

---

## 🛠️ Technology Stack

| Layer       | Technology                           | Purpose                              |
|-------------|--------------------------------------|--------------------------------------|
| **Backend** | Python Flask                         | REST API framework                  |
|             | Flask‑SQLAlchemy                    | ORM for database                    |
|             | Flask‑JWT‑Extended                  | Authentication & authorization     |
|             | OpenAI API (optional)               | Advanced sentiment analysis         |
|             | TextBlob / NLTK                     | Fallback NLP (offline)             |
| **Database**| SQLite / PostgreSQL                 | Development / production storage   |
| **Frontend**| React 18 + TypeScript               | User interface                     |
|             | Tailwind CSS                        | Styling & responsiveness           |
|             | Recharts                            | Data visualisation                 |
|             | Lucide React / Heroicons           | Icons                              |
|             | Axios                               | API communication                  |
| **DevOps**  | Docker                              | Containerisation (optional)        |
|             | AWS EC2 / Replit                   | Deployment targets                 |

---

## 📊 Performance Metrics (as of Dec 2024)

| Metric                      | Achieved         | Status      |
|-----------------------------|------------------|-------------|
| Sentiment classification    | **87.3%** accuracy | ✅ Exceeded |
| Processing time per article | **1.2‑1.8 sec**   | ✅ Exceeded |
| Concurrent analysis         | 100+ articles     | ✅ Achieved |
| System Usability Scale (SUS)| **76.5 / 100**    | ✅ Achieved |
| User satisfaction (pilot)   | **4.3 / 5**       | ✅ Achieved |

---

## 🗂️ Project Structure

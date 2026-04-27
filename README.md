# 🌐 Multilingual Instagram Analysis & Translation System

## 📌 Overview

This project implements a **scalable multilingual analysis pipeline** for Instagram data. It focuses on:

* Language detection of captions
* Cross-lingual translation to English
* Engagement analysis across languages
* Interactive dashboard for insights

The system is designed to handle **large-scale social media data** and extract meaningful patterns from multilingual content.

---

## 🚀 Key Features

* 🌍 **Language Classification**
  Detects the language of Instagram captions

* 🔁 **Translation Pipeline**
  Translates captions from multiple Indic languages to English

* 📊 **Engagement Analysis**
  Analyzes likes, comments, and shares across languages

* 📈 **Visualization Dashboard**
  Interactive dashboard to explore:

  * Language distribution
  * Engagement trends
  * Translation comparisons

---

## 🧠 Pipeline Architecture

```text
Instagram JSON Data
        ↓
Data Loading & Cleaning
        ↓
Language Detection
        ↓
Text Preprocessing
        ↓
Translation (Multilingual → English)
        ↓
Feature Extraction (caption length, engagement stats)
        ↓
Analysis & Visualization
        ↓
Interactive Dashboard
```

---

## 📂 Dataset Structure

Each record contains:

* **User Data**: user_id, username, followers, following
* **Content Data**: post_id, caption, language, timestamp
* **Engagement Data**: likes_count, comments_count, shares_count
* **Metadata**: location

---

## 📊 Dashboard Insights

The dashboard provides:

* 🌍 Language distribution across posts
* 📊 Engagement patterns by language
* 📈 Likes distribution
* 🔁 Original vs translated caption comparison
* 📏 Caption length vs translated length analysis

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Hugging Face Transformers (Translation Models)
* Plotly (Visualization)
* ipywidgets (Interactive UI)

---

## ⚡ Scalability Notes

* Supports large datasets (~500k samples)
* Batch processing for translation
* GPU acceleration for model inference

---

## 🎯 Future Improvements

* Add sentiment analysis
* Improve translation evaluation (BLEU, METEOR)
* Incorporate image-based features
* Deploy as a full web app (Streamlit/Dash)

---

## 🧩 Conclusion

This project demonstrates how multilingual social media data can be:

* Standardized using translation
* Analyzed across languages
* Visualized for actionable insights

It serves as a foundation for **cross-lingual social media analytics systems**.

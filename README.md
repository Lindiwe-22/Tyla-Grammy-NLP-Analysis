# 🎵 Analyzing the Global Pulse of Tyla's Grammy Success

> NLP sentiment analysis of public reactions to Tyla's historic Grammy wins using YouTube comments, featuring advanced visualizations and a dual sentiment analysis approach.


---

## 📋 Table of Contents

- [Business Understanding](#business-understanding)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [Setup](#setup)
- [Approach](#approach)
- [Status](#status)
- [Credits](#credits)

---

## 💼 Business Understanding

South African artist Tyla made history with her Grammy victories in 2024 and 2026, bringing her "Popiano" sound to global audiences. This project moves beyond anecdotal social media trends to provide a data-driven assessment of her cultural resonance internationally.

**Primary Objective:** Determine whether international discourse reflects a genuine shift in the global music landscape, or merely a transient digital moment.

**Business Value:** For stakeholders in the music and entertainment sectors, this project provides a blueprint for data-driven brand management. The ability to quantify sentiment allows labels and management teams to:
- Measure the ROI of award season visibility
- Identify high-growth geographic markets
- Conduct scalable market research and competitive analysis
- Gain a competitive edge in understanding audience sentiment before committing to major marketing expenditures or international tours

---

## 📸 Screenshots

> *Visualization screenshots will be added here.*

| Sentiment Distribution | Word Cloud | Comparative Model Output |
|---|---|---|
| ![Sentiment Chart](#) | ![Word Cloud](#) | ![Model Comparison](#) |

---

## 🛠️ Technologies

**Languages & Environment**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Data & Processing**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**NLP & Sentiment Analysis**

![NLTK](https://img.shields.io/badge/NLTK%20%7C%20VADER-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TextBlob](https://img.shields.io/badge/TextBlob-FF6F00?style=for-the-badge&logo=python&logoColor=white)

**Visualisation**

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![WordCloud](https://img.shields.io/badge/WordCloud-E34F26?style=for-the-badge&logo=python&logoColor=white)

**APIs**

![YouTube API](https://img.shields.io/badge/YouTube%20Data%20API%20v3-FF0000?style=for-the-badge&logo=youtube&logoColor=white)

| Category | Tools |
|---|---|
| **Data Acquisition** | YouTube Data API v3, Python |
| **Preprocessing** | Pandas, Regular Expressions (Regex) |
| **Sentiment Analysis** | VADER, TextBlob |
| **Visualisation** | Seaborn, Matplotlib, WordCloud |

---

## ⚙️ Setup

```bash
# Clone the repository
git clone https://github.com/your-username/tyla-sentiment-analysis.git
cd tyla-sentiment-analysis

# Install dependencies
pip install -r requirements.txt

# Add your YouTube Data API v3 key
export YOUTUBE_API_KEY="your_api_key_here"

# Run the analysis
python main.py
```

> **Note:** A valid [YouTube Data API v3](https://developers.google.com/youtube/v3) key is required for data acquisition.

---

## 🔍 Approach

### 1. Data Acquisition
Public comments were extracted programmatically from YouTube using the YouTube Data API v3. YouTube was selected after strategic pivots away from Twitter/X (prohibitive API costs) and Reddit (restrictive developer terms), as it provides a rich, multicultural dataset capturing Tyla's global reach — from South Africa to the United States and Brazil.

### 2. Preprocessing
Raw social media text was cleaned and standardized using Regex and Pandas to handle noise, informal language, and emoji-heavy content.

### 3. Dual-Model Sentiment Analysis
A comparative approach was used to validate results across different communication styles:
- **VADER** — tuned for informal, emoji-heavy social media language; ideal for capturing high-energy fan reactions
- **TextBlob** — provides a formal linguistic polarity baseline, useful for filtering "news-style" comments

This dual-model strategy ensures nuanced, accurate sentiment classification rather than a one-size-fits-all score.

### 4. Visual Analytics
Sentiment distributions, thematic clusters, and word clouds were generated to communicate findings clearly and accessibly.

### Key Results
- **81.2%** of comments classified as **positive**
- **6.2%** of comments classified as **negative**
- Positive-to-negative ratio of approximately **13:1**
- Top thematic keywords: *pride*, *South Africa*, *Grammy*

These findings indicate an overwhelmingly positive global brand reception, with Tyla's success deeply tied to a sense of national and continental pride.

---

## 📌 Status

![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

The analysis pipeline is complete. Future iterations may include:
- Expansion to additional platforms (e.g., TikTok, Instagram)
- Geographic sentiment mapping
- Longitudinal tracking post-Grammy cycles

---

## 🙏 Credits

**Developed by Lindiwe Songelwa**

| Platform | Link |
|---|---|
| 💼 LinkedIn | [Lindiwe S.](https://www.linkedin.com/in/lindiwe-songelwa) |
| 🌐 Portfolio | [Creative Portfolio](https://lindiwe-22.github.io/Portfolio-Website/) |
| 🏅 Credly | [Lindiwe Songelwa – Badges](https://www.credly.com/users/samnkelisiwe-lindiwe-songelwa/badges#credly) |

---

*© 2026 Lindiwe Songelwa. All rights reserved.*

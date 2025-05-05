# 🎯 ExamBuddy Recommender – Topic-Based YouTube Video Search for NCERT & GATE
Live Link : https://davproject12240850.streamlit.app/

## 📘 Project Overview

**ExamBuddy Recommender** is a smart, automated system that curates and recommends high-quality educational YouTube videos for:

- 🏫 **NCERT Classes 6 to 8** – Science, Maths, SST  
- 🎓 **GATE and Aptitude Preparation** – Logical reasoning, engineering topics

Built using Python, Selenium, and a Large Language Model (LLM), the system supports **topic-based search** and **natural language queries** via a chatbot interface — making educational content discovery seamless for school students and competitive exam aspirants.

---

## 💡 Key Features

### 🔎 Intelligent Video Discovery
- Uses automated scraping from **YouTube** and the **National Digital Library of India (NDLI)**
- Searches based on **class, subject, topic, or keyword**

### 🧠 LLM-Based Metadata Tagging
- Each video is enriched with AI-generated metadata:
  - Class & Subject (e.g., Class 7 Science)
  - Topic/Chapter mapping (e.g., “Nutrition in Animals”)
  - Short AI summary for chatbot response

### 💬 Chatbot Interface
- Ask natural language queries like:
  > "Show me videos for Class 8 Maths – Algebra"  
  > "I want GATE videos on Digital Logic"  
  > "How does reproduction in plants happen?"

- The system returns the most relevant video links instantly.

### 📁 Structured Outputs
- Cleaned and structured `.csv` files for:
  - NCERT video data
  - GATE & Aptitude videos
  - NDLI academic content

---

## 📚 Data Sources

- **YouTube**:  
  Topic-focused scraping with filters for educational tone, clarity, and English language content.

- **NDLI (National Digital Library of India)**:  
  Academic repository used to supplement school and exam-level topics.

- **Manual Quality Filtering**:  
  Only videos with relevant durations, clear visuals, and focused teaching are included.

---

## 🚀 Future Enhancements

- 🎙 **Transcript Summarization**:  
  Extract and summarize content using automatic speech recognition + LLM.


- 💬 **Advanced Chatbot Interface**:  
  Deploy chatbot on web/app with user-friendly filtering and search.

- 🧪 **User Feedback Integration**:  
  Let users rate videos and improve the recommendation engine.

---



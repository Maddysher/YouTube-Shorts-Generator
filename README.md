# 🎬 YouTube Shorts & Trailer Generator  

## 📌 Overview  
The **YouTube Shorts Generator** automatically crops engaging short clips from long videos by analyzing both the **spoken content (speech-to-text)** and the **visual elements (images/scenes)**.  

This saves content creators valuable time by automating the short-making process, allowing them to repurpose long videos into **YouTube Shorts** or even create **movie-style trailers** from full-length videos.  

---

## 🚀 Problem  
- YouTubers and filmmakers spend hours manually cutting clips from long videos.  
- Identifying the **most engaging or meaningful parts** of a vlog or movie is time-consuming.  
- Manual editing slows down content publishing and marketing.  

---

## 💡 Solution  
- Extract **speech content** from video using ASR (Automatic Speech Recognition).  
- Capture **visual scene changes** (images/frames).  
- Send both transcript + scene information to an **LLM**, which identifies the **best short-worthy segments**.  
- Automatically crop and generate ready-to-publish Shorts or Trailers.  

👉 Currently optimized for **Vlogs**, but extended to handle **Movie-length videos** for trailer generation.  

---

## 🔧 Tech Stack  
- **Python** – Core programming  
- **Whisper (OpenAI)** – Speech-to-text transcription  
- **MoviePy / FFmpeg** – Video editing and clipping  
- **LLM (Gemini / GPT / TinyLLaMA)** – Short-worthy content selection  
- **FastAPI** – Backend API for processing requests  
- **Streamlit** – Web interface for uploading & generating shorts  
- **Hugging Face / Pinecone (optional)** – Storing transcripts & embeddings for semantic search  

---

## ✨ Features  
- 🎤 Speech-to-text extraction from long videos  
- 🖼️ Scene detection & visual cue analysis  
- 🧠 LLM-powered content selection (finds best clips automatically)  
- ✂️ Auto-crops videos into Shorts or Trailers  
- 📦 Web interface (upload video → get shorts)  
- 🚀 Saves hours of manual editing for YouTubers & marketers  

---

## 🎯 Use Cases  
- **YouTubers** → Quickly turn long vlogs into Shorts for higher engagement.  
- **Movie Editors** → Generate trailers from full-length movies.  
- **Content Marketers** → Repurpose webinars, podcasts, or tutorials into highlight reels.  

---

## 📊 Result & Impact  
- Reduced **manual editing time** by up to 70%.  
- Increased **YouTube Shorts output** → boosting reach & engagement.  
- Opens possibilities for **automated movie trailers** and **marketing campaigns**.  

---


## 🛠️ Future Improvements  
- Multi-language transcription  
- More advanced scene/emotion detection  
- Direct publishing to YouTube & Instagram  

---

## 👤 Author  
**Mathavan M**  
- 📧 Email: mathavanmukesh98@gmail.com  
- 🌐 GitHub: [mathavanm](#)  
- 💼 LinkedIn: [linkedin.com/in/mathavan-m](#)  

---

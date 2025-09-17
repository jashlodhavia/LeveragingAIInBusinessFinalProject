# EarningsCallAI 🎧📊  
**AI-Powered Earnings Call Sentiment Analysis**

EarningsCallAI is a web-based application that lets you upload earnings call audio files (MP3/WAV/M4A) and get **real-time sentiment analysis** for investor communication. It provides an intuitive UI to visualize **Positive, Negative, and Neutral segments** — both as audio clips and text highlights.

---

## 🚀 Features
- **Upload Earnings Call Audio:** Supports MP3, WAV, M4A (up to 500MB).
- **AI-Powered Sentiment Detection:** Classifies speech into Positive, Negative, and Neutral segments.
- **Dynamic Results Dashboard:**  
  - Displays **counts** of each sentiment type.  
  - Renders text snippets and corresponding audio clips.  
  - Groups results by sentiment category for easier navigation.
- **Export Results:** Download processed results for offline analysis.
- **Clean UI:** Simple, dark-themed design optimized for focus.

---

## 🖼️ Demo
### Landing Page
Upload your earnings call audio:
![Landing Page Screenshot](assets/landing_page.png)

### Results Page
View sentiment counts, audio snippets, and text segments:
![Results Page Screenshot](assets/results_page.png)

---

## 🏗️ Tech Stack
- **Frontend:**  
  - HTML, CSS, JS (works on GitHub Pages)
- **Backend:**  
  - Python Flask API for processing audio and running sentiment model
- **Storage:**  
  - Supabase Storage (for saving audio + results)
- **AI/ML:**  
  - Speech-to-text (OpenAI Whisper / AssemblyAI / Google STT)  
  - Sentiment classification (custom or HuggingFace transformer)

---

## 📂 Project Structure



# 🩺 ArogyaSaathi – Voice-based Medical Info Buddy

**ArogyaSaathi** is an AI-powered health companion that simplifies complex medical reports and prescriptions for everyday users — especially the elderly and regional language speakers.  
Using OCR, GPT-powered NLP, multilingual translation, and lifelike Murf AI voiceovers, ArogyaSaathi helps users understand their health in **Marathi, Hindi, or English** — through voice.

---

## 🚀 Features

### 🔍 Medical Report Understanding
- Upload **medical prescriptions or reports** (PDF/image)
- AI extracts key information:
  - Conditions
  - Medicines & dosages
  - Symptoms
  - Tests
  - Diagnoses

### 🧠 Simplified Explanation
- Uses **OpenAI GPT API** to break down technical jargon
- Converts medical text into **easy-to-understand summaries**

### 🌐 Multilingual Translation
- Translates simplified content into:
  - 🇮🇳 Marathi
  - 🇮🇳 Hindi
  - 🇬🇧 English (default)

### 🔊 Voice Output via Murf AI
- Converts summaries into **natural-sounding audio**
- Optimized for non-readers and elders

---

## 🧠 Smart Add-ons

### 🧍 Symptom Analysis
- Extracts symptoms from the report
- (Optional) Uses web search to summarize conditions
- Provides “when to visit doctor” tips

### 💊 Medication Insights
- Explains usage, dosage, side effects
- Precaution tips included

### 🥗 Diet Recommendations
- Suggests condition-specific food:
  - Diabetic → low sugar
  - Anemia → iron-rich foods
- Examples include **Indian home foods**

### 🧘 Mental Well-being Tips
- Audio-based mindfulness prompts
- Murf AI gives calming affirmations for chronic stress

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|------------|
| 📱 Mobile App | React Native (with Expo) |
| 🔐 Backend / Auth | Supabase |
| 📁 File Upload / DB | Supabase Storage + PostgreSQL |
| 📄 OCR | `react-native-text-recognition` (for images), `pdf-parse` (for PDFs) |
| 🧠 NLP + Summarization | OpenAI GPT API |
| 🌐 Translation | Google Translate API (or IndicTrans for better regional support) |
| 🔊 Voice AI | Murf AI API |
| 🔔 Notifications | `expo-notifications` (for medicine reminders) |
| 🌐 Optional Admin Panel | Next.js (Vercel deploy ready) |

---

## ⚙️ How It Works

UPLOAD (PDF/Image)
↓
OCR (Text Extraction)
↓
Simplify (GPT Summarizer)
↓
Translate (to Hindi/Marathi)
↓
Voice Output (Murf AI)
↓

AI Bot for Diet, Wellness, Medication Tips

Notifications for Reminders

📅 Roadmap
 OCR (image + PDF)

 GPT Summary

 Murf Voice Output

 Hindi + Marathi translation

 Medicine Reminder notifications

 Admin Panel (Next.js)

 Wearable integration (e.g. Fitbit/Smartwatch sync)

 Offline voice support (for villages)

 This is a student project made for learning purposes only. Always consult a certified medical professional for health advice.

Made with ❤️ by JAY NAKASHE
Built for people who want tech to care, not just compute.

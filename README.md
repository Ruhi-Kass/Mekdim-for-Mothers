# 🇪🇹 Mekdim (መቅድም)

### *Empowering Mothers, Protecting Children, Elevating Doctors.*

**Mekdim** (Amharic for "Beginning") is an AI-powered super-app designed to bridge the healthcare gap in Ethiopia. It creates a unified ecosystem for mothers, children, and healthcare professionals, targeting the reduction of maternal mortality and the enhancement of clinical decision-making through localized, multilingual AI.


📱 App Preview

<p align="center">
<img src="https://lh3.googleusercontent.com/d/1KrlSt73Kn1Joq0TYjCBBzTXskQIsO8Ac" width="30%" alt="Mekdim app design" />
</p>

## 🚀 The Vision

In Ethiopia, the Maternal Mortality Ratio remains a critical challenge. **Mekdim** tackles this by:

  * **Empowering Mothers:** Providing AI-driven triage and culturally relevant health education in local languages (Amharic, Oromiffa, Tigrinya).
  * **Upskilling Doctors:** Delivering AI-summarized African health research and Continuing Medical Education (CME).
  * **Smart Matching:** Connecting rural patients to the nearest verified doctors and institutions using GPS-based matching.

-----

## 📱 App Preview

\<p align="center"\>
\<img src="[https://your-image-url.com/screen1.png](https://www.google.com/search?q=https://your-image-url.com/screen1.png)" width="30%" alt="Mother's Dashboard" /\>
\<img src="[https://your-image-url.com/screen2.png](https://www.google.com/search?q=https://your-image-url.com/screen2.png)" width="30%" alt="AI Triage Chat" /\>
\<img src="[https://your-image-url.com/screen3.png](https://www.google.com/search?q=https://your-image-url.com/screen3.png)" width="30%" alt="Doctor's CME Portal" /\>
\</p\>

-----

## ✨ Key Features

### 🤱 For Mothers & Children

  * **AI Symptom Checker:** Real-time triage trained on Ethiopian health protocols to detect "Danger Signs" (e.g., Pre-eclampsia).
  * **Pregnancy & Child Tracker:** Week-by-week guidance and immunization schedules.
  * **SOS Emergency:** One-tap location sharing with the nearest medical facility.
  * **Multilingual Support:** Voice-to-text input for low-literacy accessibility.

### 🩺 For Doctors

  * **Clinical Decision Support:** AI-powered suggestions for maternal and neonatal care.
  * **Research Hub:** Daily digests of the latest maternal health studies focused on the African context.
  * **Verified Professional Network:** Peer-to-peer case discussions and verified credentials.

### 🏥 For Institutions

  * **Content Portal:** Universities and hospitals can upload verified training modules.
  * **Analytics Dashboard:** Tracking health trends and referral patterns in real-time.

-----

## 🛠 Tech Stack

  * **Frontend:** Flutter / React Native (Offline-first architecture)
  * **Backend:** [Supabase](https://supabase.com/) (PostgreSQL, Auth, Edge Functions)
  * **AI Engine:** Google Gemini (Custom-tuned for Ethiopian medical protocols)
  * **Maps/Geo:** PostGIS for smart doctor-patient matching
  * **Storage:** Supabase Storage for medical licensing and educational media

-----

## 🏗 Database Architecture

The system uses a relational PostgreSQL schema with **Row Level Security (RLS)** to ensure medical data privacy. Key entities include:

  * `profiles`: Centralized user management (Mothers, Doctors, Institutions).
  * `ai_triage_logs`: Auditable logs of AI-patient interactions.
  * `immunizations`: Pediatric tracking for long-term child health.
  * `consultations`: Real-time chat and referral management.

-----

## 🌍 Social Impact

Aligned with **SDG 3 (Good Health and Well-being)**, Mekdim aims to:

1.  **Reduce Delay in Care:** AI triage encourages earlier clinic visits.
2.  **Bridge the Knowledge Gap:** Rural doctors gain access to world-class medical updates.
3.  **Build Trust:** Verified doctor matching reduces reliance on unverified traditional advice for critical complications.

-----

## 👥 The Team

  * **[Your Name/Team Name]** - Developers, Designers, and Health Tech Advocates.
  * **Hackathon:** HSIL Hackathon, Addis Ababa (April 2026).

-----

*Developed with ❤️ for a healthier Ethiopia.*
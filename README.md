# 🏥 Healthcare AI Assistant – Mediminds

An AI-powered web application that streamlines patient triage and appointment booking for clinics.  
Built with Python, Flask, and Google Gemini AI, this assistant acts as an intelligent virtual front desk — collecting patient details, analyzing symptoms, routing to the right specialist, and confirming appointments with PDF and voice output.

---

## 📌 Features & Workflow

1. **Patient Data Collection** – Collects Name, Age, Email, and Location.
2. **Age-Based Routing** –  
   - Under 18 → Pediatrician  
   - Over 65 → Geriatrician  
   - Others → AI symptom analysis.
3. **AI Symptom Analysis** – Uses **Google Gemini AI** to classify symptoms as:
   - General  
   - Emergency  
   - Mental Health.
4. **Specialist Routing** – Directs patient to appropriate specialist type.
5. **Time Slot Selection** – Non-emergency cases select from available slots.
6. **Appointment Confirmation** –  
   - Saves to **Notion database**  
   - Generates **voice confirmation** with ElevenLabs  
   - Produces a **downloadable PDF slip**.

---

## 🛠️ Tech Stack

**Backend:** Flask (Python)  
**AI:** Google Gemini 1.5 Pro  
**Database/CMS:** Notion API  
**PDF Handling:** ReportLab + PyPDF2  
**Voice:** ElevenLabs TTS  
**Config Management:** python-dotenv  
**Caching:** JSON file-based cache for AI results  

---


# n8n-resume-evaluator

**AI Resume Evaluator**  
Fully Automated AI Resume Screening Pipeline with Real-time Power BI Dashboard

![n8n](https://img.shields.io/badge/n8n-Workflow-orange)
![Groq](https://img.shields.io/badge/Groq-LLaMA--3.3--70B-green)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Google Workspace](https://img.shields.io/badge/Google%20Workspace-Integrated-blue)

---

## 🚀 Project Overview

Built live for the **BE10X AI Hackathon**.

This is a complete end-to-end AI-powered resume screening system that works exactly as shown:

- Candidate submits form → data lands in Google Sheet  
- n8n workflow automatically triggers on new row  
- Downloads resume PDF from Google Drive, extracts text  
- Groq LLaMA-3.3-70B AI evaluates and fills the following columns in real-time:  
  **ATS_Score, Skills_Match, PAR_Rating, Experience_Clarity, Overall_Grade, Recommendation, Top_Strength, Main_Gap**  
- Updates the same Google Sheet instantly  
- Sends beautiful HTML scorecard email to HR **only for shortlisted candidates**  
- Power BI Dashboard refreshes automatically with live analytics

**Result**: Zero manual screening, bias-free shortlisting, hiring time reduced from days to minutes.

---

## ✨ Key Features

- ✅ Real-time Google Sheets trigger (new form row)
- ✅ Automatic PDF download & text extraction
- ✅ AI scoring using Groq LLaMA-3.3-70B (4 dimensions)
- ✅ Smart duplicate prevention (`Processed` column)
- ✅ Conditional HTML email to HR
- ✅ Full results written back to Google Sheet with exact columns:  
  Timestamp, Name, Email, Upload your resume (PDF), ATS_Score, Skills_Match, PAR_Rating, Experience_Clarity, Overall_Grade, Recommendation, Top_Strength, Main_Gap, Processed
- ✅ Live **Power BI Dashboard** with summary, grade distribution & charts

---

## 🛠️ Tech Stack

| Component          | Technology                          |
|--------------------|-------------------------------------|
| Automation         | n8n                                 |
| AI Model           | Groq LLaMA-3.3-70B                  |
| Form & Database    | Google Forms + Google Sheets        |
| File Storage       | Google Drive                        |
| Notifications      | Gmail (HTML scorecard)              |
| Analytics          | Power BI (live dashboard)           |

---

## 📊 Power BI Dashboard

<img width="1272" height="766" alt="Screenshot 2026-03-31 235836" src="https://github.com/user-attachments/assets/9a29b710-92d8-4f2c-990b-3fdd39213161" />


---

## 🛠️ Quick Setup

1. Import `My workflow(7).json` into n8n
2. Add Google Sheets, Drive, Gmail & Groq credentials
3. Turn on the workflow
4. Connect Power BI to the same Google Sheet (auto-refresh enabled)

Full step-by-step guide is inside the Technical Specification PDF.

---

## 🙏 Acknowledgments

Built during **BE10X AI Hackathon**  
Huge thanks to @Be10X for the incredible learning experience!

---

**Made with ❤️ using n8n + Groq + Power BI**  

#AI #AIHackathon #n8n #Automation #PowerBI #ResumeScreening #HiringAutomation #AIAgents #NoCode #GenerativeAI

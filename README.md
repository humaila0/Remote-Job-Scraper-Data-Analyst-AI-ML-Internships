# 🧠 Remote Job Scraper – Data Analyst / AI / ML Internships

![Build](https://img.shields.io/badge/automation-Make.com-blue)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
![Tech](https://img.shields.io/badge/tech-stack-yellow)
![Jobs](https://img.shields.io/badge/job%20type-remote-informational)
![Target](https://img.shields.io/badge/focus-AI%2FML%2FData%20Science-purple)

This project automates the process of collecting **remote job listings** related to **Data Analyst**, **Data Science**, **Artificial Intelligence (AI)**, **Machine Learning (ML)**, and **Internships** using [Make.com](https://www.make.com/) and **Google Sheets**.

---

## 🚀 What It Does

- Fetches job posts from *We Work Remotely – Data Jobs*.
- Filters job titles using relevant keywords:
  - `data analyst`, `data science`, `AI`, `machine learning`, `intern`
- Saves matching job posts to a **Google Sheet**, including:
  - **Job Title**
  - **Company Name**
  - **Job Link**
  - **Publication Date**

---

## 🔧 How It Works

### 🔄 Scenario Built on Make.com

1. Uses the **RSS Feed** module to fetch job listings.
2. Filters the posts using keyword-based conditions.
3. Appends valid results to your **Google Sheet**.

---

## 📊 Google Sheets Output

Before running, create a Google Sheet with the following columns:

| Job Title | Company | Link | Date |
|-----------|---------|------|------|

Paste your **Google Sheet ID** into the Make scenario JSON before uploading.

---

## 🛠 Tech Stack

| Tool        | Purpose                                     |
|-------------|---------------------------------------------|
| Make.com    | Automates the workflow (RSS ➜ Filter ➜ Sheet) |
| RSS Feed    | Provides live job listings                  |
| Google Sheets | Stores the filtered job results          |
| JSON        | Format for importing the automation scenario |

---

## 📂 Files

- `remote-job-scraper-scenario.json` — Make.com automation scenario (import into your Make dashboard)
- `README.md` — Project documentation

---

## ✅ Prerequisites

- A **Make.com** account
- A **Google Sheet** shared with:  
  `make.com@apps.integromat.com`
- Activated Make.com connections for:
  - **Google Sheets**
  - **RSS Feed module**

---

## 🕒 Scheduling (Optional)

You can set the scenario to run automatically every few hours to keep your job listings up to date.

---

## 🔐 Security Note

This scenario only:
- Reads from a public RSS feed
- Writes to a private Google Sheet

**No login credentials or sensitive data** are stored or exposed in the shared JSON file.

---

## 📌 Use Cases

Perfect for:

- Students and job seekers in **AI**, **ML**, **Data Analytics**, or **Data Science**
- Automating internship and remote job hunting
- Creating your personal job board or tracker

---

## 💡 Customization Tip

You can easily **edit the filters** inside Make.com to:
- Target specific roles
- Focus on keywords or companies you're interested in

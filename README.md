Remote Job Scraper – Data Analyst / AI / ML Internships
This project automates the process of collecting remote job listings related to Data Analyst, Data Science, AI, Machine Learning, and Internships using Make.com and Google Sheets.

🚀 What It Does
Fetches job posts from We Work Remotely – Data Jobs

Filters job titles with keywords: data analyst, data science, AI, machine learning, intern

Saves relevant jobs into a Google Sheet with:

Job Title

Company Name

Job Link

Publication Date

🔧 How It Works
Scenario Built on Make.com

Uses the RSS feed module to fetch job posts.

Filters posts using keyword-based conditions.

Appends valid results to Google Sheets.

Google Sheets Output

You need to create a sheet with columns: Job Title, Company, Link, Date

Paste your Google Sheet ID inside the scenario JSON before uploading.

🛠 Tech Stack
Tool	Purpose
Make.com	Automates the workflow (RSS ➜ Filter ➜ Google Sheets)
RSS Feed	Source for live job listings
Google Sheets	Stores the filtered job results
JSON	Format for importing the automation scenario

📂 Files
remote-job-scraper-scenario.json — The Make scenario file (import into your Make dashboard)

README.md — Project documentation

✅ Prerequisites
A Make.com account

A Google Sheet (shared with make.com@apps.integromat.com)

Activated Make.com connections for:

Google Sheets

RSS module

🔄 Scheduling (Optional)
You can schedule this scenario to run automatically every few hours to keep your sheet updated with new jobs.

🔐 Security Note
This scenario only reads from a public RSS feed and writes to your private Google Sheet. No credentials are stored in the shared JSON file.

📌 Use Case
Ideal for:

Students and job seekers in AI/ML/Data fields

Automating internship hunting

Building a personal job board or tracker

💡 Tip
You can customize the filters in the scenario to match your specific interests or target job titles.


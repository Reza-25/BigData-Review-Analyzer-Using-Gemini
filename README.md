# 🚀 AI-Powered Customer Sentiment & Business Insight Analyzer
💡 The Problem
E-commerce businesses receive thousands of reviews daily. Identifying core product issues from a sea of raw text is time-consuming and expensive.

🎯 The Solution
An automated pipeline that ingests massive amounts of customer reviews using Apache Spark (Databricks), filters critical feedback, and leverages Generative AI (LLM) to instantly generate actionable business insights.

🛠️ Tech Stack
Data Processing: Databricks Community Edition, PySpark

AI & NLP: Gemini Pro API (via Prompt Engineering)

Language: Python

📈 How It Works (Pipeline)
Ingestion: Load raw CSV dataset (100k+ rows) into Databricks.

Transformation: Clean and filter 1-star & 2-star reviews using PySpark for high-performance distributed computing.

AI Summarization: Pass aggregated complaints to the LLM API.

Output: Generate a structured "Business Action Plan" (JSON format).

🖼️ Sneak Peek
<img width="1352" height="757" alt="Screenshot 2026-04-17 094800" src="https://github.com/user-attachments/assets/80f94a06-4996-409e-be47-5789234b3bbb" />
<img width="1340" height="780" alt="Screenshot 2026-04-17 094816" src="https://github.com/user-attachments/assets/cf5154d0-d416-4c40-a442-914c6471590a" />
<img width="1349" height="702" alt="Screenshot 2026-04-17 094833" src="https://github.com/user-attachments/assets/aae6ffdc-9420-4866-8785-96313925f3c7" />

💼 Business Value (Kenapa ini penting buat Klien?)
Cuts down manual review analysis time by 95%.

Helps Product Managers pinpoint exact hardware/software defects based on real user sentiment instantly.

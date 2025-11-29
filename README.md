# Automated-Data-Analysis-Pipeline-using-n8n
# AI-Powered Automated Data Analytics Pipeline (n8n + Supabase + Quadratic AI)

This project is a fully automated ETL + AI analytics workflow built using **n8n**, **Supabase PostgreSQL**, and **Quadratic AI**.  
The system extracts CSV reports from email, cleans and transforms data, loads it into a cloud database, and generates AI-powered insights automatically.

---

## 🚀 Features

### 🔁 Automated ETL Pipeline (n8n)
- Gmail Trigger to capture daily sales emails
- Extracts and parses CSV attachments
- Date & data format normalization
- Schema mapping and validation
- Inserts cleaned data into Supabase PostgreSQL

### 🗄 Database Layer (Supabase)
- Fact tables:
  - `fact_aggregate`
  - `fact_order_line`
- Optimized with proper data types, constraints & indexing

### 🤖 AI-Powered Analysis (Quadratic AI)
- Automated data validation
- KPI generation
- Trend analysis
- Summary and insights using AI prompts

### ⚙ Tools Used
- n8n (automation / ETL)
- Supabase (Postgres database)
- Quadratic AI (LLM powered analysis)
- Python (data cleaning)
- SQL (schema & transformations)

---

## 📂 Project Structure

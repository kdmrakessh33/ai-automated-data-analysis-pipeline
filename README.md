**AI-Driven Automated Data Analysis Pipeline**

**Tools Used**: n8n | Gmail API | Supabase (PostgreSQL) | Quadra AI | CSV | Data Automation

**📘 Project Overview**

This project demonstrates how AI and automation can eliminate manual data-handling in analytics workflows.

The pipeline automatically:
Fetches incoming emails with specific subjects using Gmail Trigger (via n8n).
Extracts attached CSV files automatically.
Loads the data into a PostgreSQL database hosted on Supabase.
Connects the Supabase database to Quadra for AI-driven data cleaning and analysis.
Allows me to ask business questions in plain English and receive accurate analytical answers.


**⚙️ Workflow Architecture**
<img width="1185" height="540" alt="image" src="https://github.com/user-attachments/assets/262a8479-4596-4a86-8c69-2fd226c41940" />


**🔍 AI Analysis Flow** https://app.quadratichq.com/file/a85ccce6-3b12-4566-89c5-dd82ef414d67

Once data is loaded to Supabase, it is connected to Quadra, an AI-powered analytics platform.

I performed:
Data cleaning using AI-assisted SQL generation.
Prompt-based analysis
Quadra returned accurate, explainable insights within seconds — eliminating the need for manual SQL or Python writing.



**🧰 Tech Stack**

| Category    | Tools Used              | Purpose                                                  |
| ----------- | ----------------------- | -------------------------------------------------------- |
| Automation  | n8n                     | Email fetch, CSV extraction, and data flow orchestration |
| Database    | Supabase (PostgreSQL)   | Data storage and structured querying                     |
| AI Analysis | Quadra                  | Prompt-driven data exploration and insight generation    |
| Data Source | Gmail Attachments (CSV) | Input data received from business sources                |

**💡 Key Highlights**

Fully automated ETL process (no manual download/upload).
Prompt-based analytics — no manual coding required for insights.
Integration of open-source tools (n8n + Supabase) with AI-powered analytics.
Scalable design that can be adapted for any business domain.

**🚀 Impact / Outcome**

Reduced manual report generation time from hours to minutes.
Demonstrated how AI can empower analysts to focus on business insights, not data wrangling.
End-to-end working pipeline showcasing automation + AI synergy.

**🧠 Skills Demonstrated**

Automation • ETL Design • SQL / Supabase • Data Cleaning • AI Analytics • Prompt Engineering • Workflow Orchestration

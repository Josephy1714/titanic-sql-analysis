# titanic-sql-analysis
Titanic SQL Analysis & Model Diagnostics
🔍 Project Overview
This project explores the Titanic dataset using SQL in DB Browser for SQLite, followed by a modeling attempt in Google Colab. The goal was to analyze survival patterns, build a predictive model, and diagnose performance limitations using SQL — a rare and powerful skill in data science.

🛠️ Tools Used
DB Browser for SQLite – for SQL querying and data export

Google Colab – for Python modeling and evaluation

Pandas, scikit-learn – for data preprocessing and machine learning

### 📊 SQL Workflow Highlights

| Step | Task                            | SQL Skill                         |
|------|---------------------------------|-----------------------------------|
| 1–3  | Previewed raw data              | `SELECT`, `LIMIT`                 |
| 4    | Counted total passengers        | `COUNT(*)`                        |
| 5    | Gender breakdown                | `GROUP BY`, `COUNT(*)`            |
| 6    | Class distribution              | `GROUP BY`, `COUNT(*)`            |
| 7    | Average age by class            | `AVG()`, `ROUND()`                |
| 8    | Survival by gender              | `SUM()`, `ROUND()`, conditional math |
| 9    | Survival by class               | Same as above                     |
| 10   | Missing age check               | `WHERE IS NULL`                   |
| 11–13| Age & fare distribution         | `GROUP BY`, `AVG()`               |
| 14   | Embarkation port breakdown      | `GROUP BY Embarked`               |
| 15   | Exported cleaned table          | `CREATE TABLE`, `WHERE` filters   |

📉 Modeling Attempt
Built a survival prediction model using Sex, Pclass, Age, Fare, and Embarked

Achieved 0.52 accuracy in Colab

Used SQL to diagnose model limitations:

Survival rates were nearly 50/50 across all groups

Dataset was likely synthetic or randomized

No strong patterns for the model to learn

🧠 Key Insight
“Even the best model can’t learn from random data. SQL helps us prove it.”

This project demonstrates that data quality and structure matter more than model complexity, and that SQL is a powerful tool for critical thinking and model validation.

👨‍🎓 About Me
Joseph Ombati First-year Data Science student at the University of Nairobi Focused on modular Python workflows, ethical automation, and cinematic web platforms 🔗 LinkedIn 🔗 GitHub

📌 Tags
#DataScience #SQL #Interncred #ModelDiagnostics #TitanicDataset #MachineLearning #SQLite #UniversityOfNairobi #Python #StudentProjects #GlobalTech #AI #EthicalAutomation #ModularWorkflows

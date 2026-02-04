# 👋 Hi, I'm Kashyap Ava  

🎓 **M.S. in Statistics @ UIUC** | 🧠 **Data Scientist focused on Statistical Modeling, Data Pipelines & Applied ML**  

I design and build **reproducible data science systems** that connect modeling, analytics, and data engineering.  
My work combines **statistical rigor, machine learning, and end-to-end pipeline design** to transform raw data into actionable insights.  

---

## 📊 Interests  
- Time Series Forecasting  
- Predictive Modeling & Statistical Learning  
- Data Engineering (dbt, DuckDB, ETL)  
- BI Dashboards & KPI Analytics  

---

## 📁 Featured Projects  

### 📊 [Long-Term Rice Field Trial Analytics (Mixed-Effects Modeling & Trial QC)](https://github.com/KashyapAva/field-trial-mixed-models)
Analyzed **50+ years of irrigated rice field-trial data** using **mixed-effects models** to quantify nitrogen response and cultivar performance across seasons.
Fit a **split-plot RCBD** with **Nitrogen (main-plot) × Cultivar (subplot)** using mixed-effects models (random Year × Rep effects) for valid inference.
Performed **trial QC**: outlier checks, block consistency, and **ARM-style plot heatmaps** to evaluate field uniformity without GPS coordinates.
Identified nitrogen plateau in wet seasons (NUE limits) and maximum yield gain in the dry season, with **V4 as the most stable cultivar**.
Delivered **publication-quality visuals** and **agronomic recommendations**, translating results into field-ready guidance for R&D and agronomy teams.

---

### 🧩 [Text-to-SQL LLM Copilot (FastAPI | SQLite | OpenAI | SQLGlot)](https://github.com/KashyapAva/API-SQL-LLM)  
Built a FastAPI microservice that converts natural-language queries into validated SQL.  
Integrated OpenAI’s GPT-4o-mini with schema introspection and SQLGlot guardrails, achieving **>95% query accuracy**.  
Automated ELT with pandas + SQLAlchemy, Swagger testing, and `.env` configurations for **reproducible deployment**.  

---

### 📈 [Equity Factor Analysis with dbt + DuckDB (CAPM & Fama-French 5)](https://github.com/KashyapAva/etl-capm-ff5)  
Developed a **reproducible dbt pipeline** to ingest and test Fama-French & monthly equity data (6 models, 12 tests, 100% pass).  
Ran CAPM & FF5 regressions in Python to identify statistically significant alphas and quantify factor fits (**R² = 0.18–0.67**).  
Demonstrated **modern analytics engineering principles** using data lineage, schema testing, and modular ETL design.  

---

### 📊 [Retail KPI Dashboard](https://github.com/KashyapAva/retail-kpi-powerbi-dashboard)  
Built an end-to-end **Power BI solution** integrating multiple datasets into a unified semantic model.  
Created **15+ DAX measures** and interactive dashboards for tracking KPIs — Revenue, AOV, Gross Margin %, Conversion Rate, CAC, ROAS, and YoY Growth.  

---

### 🌾 [Methane Flux Prediction using RNN & LSTM](https://github.com/KashyapAva/methane-prediction)  
Forecasted methane emissions in maize fields using **deep learning models** trained on eddy-covariance sensor data.  
Benchmarked LSTM, Random Forest, and SARIMA models, improving **MAPE from 103% → 15%** by modeling key drivers (soil moisture, air temperature).  

---

### 💰 [Income Prediction using Logistic & Probit Models](https://github.com/KashyapAva/income-prediction)  
Predicted income > $50K on UCI Census data using logistic regression and GLMs with a **probit link**.  
Achieved **AUC = 0.894** and implemented automated preprocessing pipelines in MySQL + SAS.  

---

### ⚙️ [Reducing CO Emissions in Turbine Output](https://github.com/KashyapAva/turbine-co-reduction)  
Applied regression, LASSO, decision trees, and random forests to optimize turbine parameters and minimize CO output.  
Identified key predictors (**CDP > 12 mbar, TIT > 1085 °C**) and achieved **RMSE = 0.504**.  

---

### 🧬 [Parkinson’s Disease Progression Prediction](https://github.com/KashyapAva/parkinsons-progression)  
Predicted UPDRS scores from clinical and protein data using LSTM, LightGBM, CatBoost, and SVR models.  
Enhanced interpretability through SHAP analysis and improved progression tracking accuracy.  

---

### 🖼️ [Image Generation with GANs and DIP-VAEs](https://github.com/KashyapAva/image-generation-gan-dipvae)  
Compared **GANs vs. Disentangled VAEs** on MNIST & SVHN datasets to analyze image quality, latent structure, and training stability.  

---

### 🧮 [Optimization in Deep Networks](https://github.com/KashyapAva/implicit-acceleration)  
Theoretical study demonstrating how **overparameterization accelerates gradient descent** via implicit preconditioning.  

---

### 🚦 [Context-Aware Traffic Accident Severity Prediction](https://github.com/KashyapAva/accident-severity-prediction)  
Modeled accident severity using spatial and seasonal features with **ensemble learning** and **hotspot detection**.  
Implemented undersampling techniques to balance class distributions and improve generalization.  

---

## 🧰 Tech Stack
**Languages:** Python, R, SQL  
**Libraries:** Pandas, Scikit-learn, TensorFlow, Statsmodels, dbt, DuckDB  
**Visualization:** Power BI, Matplotlib, ggplot2  
**Data Tools:** MySQL, SQLite, SQLAlchemy, SAS  
**Cloud:** AWS, Azure  

---

### 💬 Let’s Connect  
📫 [LinkedIn](https://www.linkedin.com/in/kashyap-avs) • [GitHub](https://github.com/KashyapAva)


# 👋 Hi, I’m Kashyap Ava

🎓 **M.S. Statistics @ UIUC**  
🧠 **Data Scientist / Applied AI Engineer** — GenAI, Statistical Modeling, Analytics Engineering

I build **end-to-end, production-minded data and GenAI systems** — from ingestion and retrieval to modeling, APIs, and user-facing tools.  
My work combines **statistical rigor**, **modern ML/LLMs**, and **reproducible pipelines** to turn raw data into reliable, decision-ready insights.

---

## 🔥 Featured Projects

### 🤖 [Local RAG Chatbot (LLM, FAISS, FastAPI, Streamlit)](https://github.com/KashyapAva/local-rag-chatbot)
Built an end-to-end **local Retrieval-Augmented Generation (RAG)** system for grounded Q&A over PDF/Markdown documents.  
Implemented similarity-thresholded FAISS retrieval, deterministic local LLM inference (Phi-3-mini), and a FastAPI backend with a Streamlit demo UI, focusing on **hallucination control, explainability, and system reliability**.

---

### 🧩 [Text-to-SQL Analytics Assistant (LLM, FastAPI, SQLGlot)](https://github.com/KashyapAva/API-SQL-LLM)
Built a FastAPI microservice converting natural-language questions into **validated SQL** over a relational dataset.  
Added schema-aware prompting and SQLGlot guardrails, achieving **95%+ query accuracy** with **zero invalid SQL executions** in testing.

---

### 📈 [Equity Factor Analytics — dbt + DuckDB (CAPM & Fama-French 5)](https://github.com/KashyapAva/etl-capm-ff5)
Developed a **reproducible analytics engineering pipeline** using dbt and DuckDB with tests, lineage, and modular ELT design.  
Ran CAPM and FF5 regressions to quantify factor exposure and alpha (**R² = 0.18–0.67**), demonstrating production-style financial analytics.

---

### 🌾 [Long-Term Rice Field Trial Analytics (Mixed-Effects Modeling)](https://github.com/KashyapAva/field-trial-mixed-models)
Analyzed **50+ years of agronomic field-trial data** using mixed-effects models (split-plot RCBD) for valid inference.  
Performed trial QC, visual diagnostics, and delivered **field-ready recommendations** with publication-quality outputs.

---

## 📌 Additional Selected Projects

### 📊 [Retail KPI Dashboard (Power BI, DAX)](https://github.com/KashyapAva/retail-kpi-powerbi-dashboard)
Designed an end-to-end **Power BI analytics solution** with 15+ DAX measures to track revenue, AOV, gross margin %, CAC, ROAS, and YoY growth for retail performance monitoring.

### 🌾 [Methane Flux Prediction (LSTM, RF, SARIMA)](https://github.com/KashyapAva/methane-prediction)
Forecasted methane emissions from eddy-covariance sensor data, improving **MAPE from 103% → 15%** by modeling key environmental drivers such as soil moisture and temperature.

### 🧬 [Parkinson’s Disease Progression Modeling](https://github.com/KashyapAva/parkinsons-progression)
Predicted UPDRS progression using LSTM, LightGBM, CatBoost, and SVR models, with **SHAP-based interpretability** for clinical insight.

### 💰 [Income Prediction with GLMs (Logit & Probit)](https://github.com/KashyapAva/income-prediction)
Modeled income classification on UCI Census data using logistic and probit GLMs, achieving **AUC = 0.894** with automated preprocessing pipelines.

### ⚙️ [CO Emissions Optimization in Turbine Output](https://github.com/KashyapAva/turbine-co-reduction)
Applied regression, LASSO, and tree-based models to reduce turbine CO emissions, identifying key operational thresholds and achieving **RMSE = 0.504**.

---

## 🧠 Core Skills

**GenAI & LLM Systems**  
RAG pipelines, local LLM inference (llama-cpp), embeddings, FAISS, prompt design, hallucination control, source attribution  

**Machine Learning & Statistics**  
GLMs, mixed-effects models, classification & regression, LSTM/RNNs, SHAP, model diagnostics  

**Data Engineering & Analytics**  
FastAPI, dbt, DuckDB, ETL/ELT pipelines, SQL, data validation, reproducible workflows  

**Visualization & BI**  
Power BI, DAX, Matplotlib, ggplot2, analytical storytelling  

**Tools & Platforms**  
Python, R, SQL, Git/GitHub, Streamlit, Linux, AWS, Azure, SAS  

---

## 📫 Contact & Links
📧 **Email:** kashyap.ava.29@gmail.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/kashyap-avs  
💻 **GitHub:** https://github.com/KashyapAva  

---

⭐ *Repositories emphasize clarity, reproducibility, and system design — bridging modeling, data engineering, and applied AI.*


---
⭐ *All repositories emphasize clarity, documentation, and reproducibility — bridging data engineering, modeling, and decision-making.*


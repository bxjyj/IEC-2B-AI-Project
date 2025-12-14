# INTERNATIONAL ELITE CAPITAL 2B - Investor Relations AI Product


⚠️ _Update the above title with your AI Studio Challenge Project name. Remove all guidance notes and examples in this template before finalizing your README._

---

### 👥 **Team Members**

**Example:**

| Name             | GitHub Handle | Contribution                                                             |
|------------------|---------------|--------------------------------------------------------------------------|
| Jade Xu    | @bxjyj | Data collection, data preprocessing, data analysis, ML model design, prompt engineering, data engineering, application development, app hosting   |
| Anusha Kokala   | @anushakokala     | Data collection, data preprocessing (data manipulation & visualization, model selection + training, and feature engineering) |
| Shatakshi Tyag     | @ |               |
|  Ayooluwa Wojuade    | @       | |


---

# Investor Relations AI Matchmaking Platform

## 🎯 Project Highlights

- Developed an **AI-powered investor–company matchmaking system** leveraging **Random Forest modeling and Large Language Models (LLMs)** to address fragmented and unstructured investor relations data.
- Built a **centralized data pipeline** using **SEC EDGAR filings** to transform raw XML/JSON filings into clean, structured datasets suitable for AI analysis.
- Utilized **OpenAI embeddings** and **Claude API prompt engineering** to summarize investor profiles and identify potential investor–startup alignment more efficiently than manual research.
- Identified **key matching signals** (industry, funding stage, founder background, investment history) to improve relevance and reduce misaligned outreach for startups and investors.
- Generated actionable insights to support **International Elite Capital’s (IEC)** goal of improving discovery, visibility, and meaningful connections across startups, investors, and media stakeholders.

---

## 🏗️ Project Overview

This project was completed as part of the **Break Through Tech AI Program – AI Studio**, in collaboration with **International Elite Capital (IEC)**.

### Host Company
**International Elite Capital (IEC)** focuses on improving how startups, investors, and media discover and connect in a crowded and fragmented ecosystem.

### Project Objective
The goal of this project was to:
- Reduce data chaos in investor relations
- Improve startup visibility
- Enable smarter, AI-driven matchmaking between companies, investors, and media stakeholders

### Real-World Significance
The investor relations ecosystem relies heavily on unstructured filings, manual research, and misaligned outreach, leading to lost opportunities. This project demonstrates how **AI and LLMs can organize complex financial data**, improve match quality, and reduce the time required for investor research and outreach.

---

## 👩🏽‍💻 Setup and Installation

### 1. Clone the Repository
git clone https://github.com/your-username/iec-investor-relations-ai.git
cd iec-investor-relations-ai
### Key Dependencies
- pandas
- numpy
- scikit-learn
- matplotlib / seaborn
- openai
- requests
- jupyter

## 📊 Data Exploration

### Dataset Description
- **Source:** SEC EDGAR Filings (SEC API)
- **Format:** XML, JSON → CSV / Excel
- **Final Dataset Size:** 66 samples, 37 features
- **Data Type:** Structured and unstructured financial, company, and investor data

### Data Preparation & EDA
- Reviewed multiple SEC filings to identify relevant investor and company attributes
- Removed low-signal or inconsistent data
- Standardized features across companies and investors
- Converted long-form text into structured categorical variables
- Mapped startup traits to investor preferences

### Key Insights
- Not all SEC filings provide meaningful matching signals
- Clean data is critical for effective LLM prompting
- Investor investment patterns are often predictable based on historical data

### Challenges & Assumptions
- Small dataset limits generalizability
- Public filings may be incomplete or inconsistent
- Historical behavior is assumed to reflect future investor preferences

---

## 🧠 Model Development

### Models Used
- **Random Forest Classifier** for exploratory modeling and feature importance analysis
- **Large Language Models (LLMs):**
  - OpenAI for embeddings
  - Claude API for prompt engineering and investor discovery

### Feature Selection & Tuning
- Extracted and analyzed feature importances from the Random Forest model
- Focused on interpretable features aligned with stakeholder needs
- Minimal hyperparameter tuning due to dataset size

### Training Setup
- **Training set:** 46 samples
- **Validation set:** 10 samples
- **Test set:** 10 samples
- Evaluation focused on exploratory feasibility rather than deployment-ready accuracy

---

## 📈 Results & Key Findings

### Model Performance
- Random Forest achieved strong performance on training data
- Results are **directional** due to limited sample size
- Feature importance analysis identified key predictors for investor–startup matching

### Key Takeaways
- Data quality significantly impacts AI and LLM performance
- Aligning startup attributes with investor preferences improves match relevance
- LLMs provide faster, more consistent summaries than manual research

---

## 🚀 Next Steps

- Expand the dataset using additional SEC filings and external data sources
- Improve LLM prompt engineering for higher-quality investor discovery
- Validate AI-generated matches with real-world investor feedback
- Develop a functional web platform for deployment
- Explore fairness, bias, and explainability in investor recommendations



## 📝 **License**

If applicable, indicate how your project can be used by others by specifying and linking to an open source license type (e.g., MIT, Apache 2.0). Make sure your Challenge Advisor approves of the selected license type.

**Example:**
This project is licensed under the MIT License.

---

## 📄 **References** (Optional but encouraged)

Cite relevant papers, articles, or resources that supported your project.

---

## 🙏 **Acknowledgements** (Optional but encouraged)

Thank your Challenge Advisor, host company representatives, TA, and others who supported your project.

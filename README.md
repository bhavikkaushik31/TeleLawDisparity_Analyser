# Tele-Law Disparity Analyzer

## 📌 Project Overview
The **TeleLaw Disparity Analyzer** is a data-driven project aimed at uncovering and addressing demographic and regional disparities in legal aid access through the **Tele-Law initiative**. Despite the expansion of the initiative across Indian states and districts, there remains a limited understanding of utilization patterns across gender, caste, and geography.  
This project leverages **IBM Cloud Lite** services and machine learning to analyze official Tele-Law case registration datasets, normalize for CSC (Common Service Center) availability, and predict underserved regions and communities.

---

## 🎯 Problem Statement
Despite the expansion of the Tele-Law initiative across states and districts, there is limited understanding of demographic utilization patterns and regional disparities in legal aid access.  
The challenge is to:
- Analyze Tele-Law case registration data to uncover **gender-wise, caste-wise, and geographic disparities**.
- Identify uneven representation among marginalized groups (**SC, ST, OBC**) and low outreach areas.
- Normalize for the varying number of CSCs per region to ensure fair comparisons.
- Deliver a **data-driven approach** to evaluate inclusivity and optimize service delivery.

Dataset Link: [District-wise Tele-Law Case Registration Data](https://www.data.gov.in/resource/district-wise-tele-law-case-registration-and-advice-enabled-data-fy-2021-22-2024-25)

---

## 💡 Proposed Solution
The **TeleLaw Disparity Analyzer**:
- **Data Preprocessing:** Clean, standardize, and normalize demographic and geographic data.
- **Feature Engineering:** Compute utilization ratios, disparity indicators, and per-CSC metrics.
- **Analysis & Prediction:** Use **IBM WatsonX AI** to train models for disparity detection and forecasting.
- **Visualization:** Create interactive charts, maps, and reports for clear interpretation.
- **Deployment:** Provide APIs for integration into dashboards and policy decision tools.

**Key Benefits:**
- Enables targeted outreach to marginalized communities.
- Provides data-backed insights for equitable resource allocation.
- Supports policy transparency and accountability.

---

## 🛠️ Technology Stack
- **Programming Language:** Python
- **Data Handling:** `pandas`, `numpy`
- **Machine Learning:** IBM WatsonX AI SDK, `scikit-learn`
- **Visualization:** `matplotlib`, `seaborn`
- **Platform:** IBM Watson Studio, WatsonX AI
- **Environment:** Jupyter Notebook (development), WatsonX API (deployment)

---

## ⚙️ Algorithm & Deployment Steps
1. **Data Preprocessing**
   - Load and clean Tele-Law dataset.
   - Handle missing values and duplicates.
   - Normalize demographic feature values.
2. **Feature Engineering**
   - Calculate gender ratio, caste proportion, and utilization metrics.
   - Create disparity indicators.
3. **Model Training**
   - Use WatsonX AI AutoAI pipeline for supervised classification.
   - Apply train-test split and validation.
4. **Deployment**
   - Deploy trained model as REST API on IBM WatsonX AI.
   - Integrate API into dashboards for real-time disparity analysis.
     <img width="940" height="411" alt="image" src="https://github.com/user-attachments/assets/8150bd63-fff0-4073-bfb2-64ecbc05d477" />


---

## 📊 Results
- Identified inequities in Tele-Law service utilization across gender and caste categories.
- Demonstrated the effectiveness of combining AI with public datasets for actionable intelligence.
- Provided a foundation for data-driven policy improvements.
  <img width="1140" height="609" alt="image" src="https://github.com/user-attachments/assets/260947b4-3854-447b-a43d-7144fda2d214" />


---

## 🔮 Future Scope
- Integration with **real-time Tele-Law logs** for live monitoring.
- Expansion to other socio-economic attributes (e.g., income, education level).
- Development of a **public-facing interactive dashboard**.
- Inclusion of **NLP** to analyze case descriptions and detect hidden bias.
- Predictive modeling for future disparity trends and resource allocation.

---

## 📚 References
- [Ministry of Law and Justice – TeleLaw Scheme Overview](https://www.legalaffairs.gov.in)  
- [Tele-Law Case Registration Dataset](https://www.data.gov.in/resource/district-wise-tele-law-case-registration-and-advice-enabled-data-fy-2021-22-2024-25)  
- [IBM WatsonX AI Documentation](https://dataplatform.cloud.ibm.com/docs)  
- [Scikit-learn](https://scikit-learn.org)  
- [Pandas Documentation](https://pandas.pydata.org)

---

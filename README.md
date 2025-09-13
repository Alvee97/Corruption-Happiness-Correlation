# 🌍 Corruption & Happiness Correlation Analysis  

### 📖 Project Story  
This project was developed as part of **DSO 510: Business Analytics** at USC Marshall.  
Our group set out to analyze the relationship between **corruption levels in countries** and the **happiness of their populations**, using global datasets. While corruption is often assumed to decrease happiness, our research explored multiple perspectives:  
- 📉 **Negative Relationship**: Higher corruption → Lower happiness (due to inequality, poor services, lack of trust).  
- 📈 **Positive Relationship**: Higher corruption → Higher happiness (as a "bureaucratic lubricant" that simplifies rigid systems).  
- ⚖️ **No Significant Relationship**: Happiness may be shaped more by confounders such as GDP, culture, healthcare, and safety.  

---

## 📂 Files in this Repository  

1. **`DSO 510 Report.docx`**  
   - Full written report explaining hypotheses, methodology, and findings.  

2. **`DSO510_Project.pptx`**  
   - Final presentation slides with key insights and visualizations.  

3. **`DSO 510 Project Data Visualizations.ipynb`**  
   - Jupyter Notebook containing data cleaning, merging, visualization, and regression models.  

---

## 📊 Methodology  

1. **Data Sources**  
   - *World Happiness Report 2023* → Happiness Index (GDP, social support, life expectancy, freedom, generosity, corruption perception).  
   - *Transparency International 2023* → Corruption Perception Index.  
   - *WHO* → Health data.  
   - *Global Hunger Index* → Food security data.  
   - *UNDP Human Development Index* → Development metrics.  
   - *Statista / Kaggle* → GDP, population, supplementary data.  

2. **Data Preparation**  
   - Compiled multiple datasets into a single panel using common **country codes**.  
   - Handled missing data (countries absent in one dataset assigned placeholder `-1`).  
   - Standardized metrics for comparison.  

3. **Analysis & Visualizations**  
   - Scatter plots & regression lines for corruption vs. happiness.  
   - Boxplots to compare happiness in high vs. low corruption countries.  
   - Correlation matrices to explore confounders.  
   - Linear & multiple regression models to test significance of variables.  

---

## 🔑 Key Findings  

- Countries with **higher corruption generally scored lower on happiness**, confirming a negative correlation.  
- Some exceptions existed where corruption acted as a **“bureaucratic lubricant”**, increasing short-term happiness in rigid bureaucratic systems.  
- Happiness is **multi-factorial** — GDP per capita, healthcare, social support, and safety often overshadow corruption’s effect.  
- Developed vs. Developing nations showed different trends, emphasizing the role of **context and confounding factors**.  

---

## ⚙️ Tools & Skills Highlighted  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels)  
- **Data Merging & Cleaning** (multi-source datasets, country code mapping)  
- **Regression Analysis** (simple & multiple linear regression)  
- **Data Visualization** (scatterplots, boxplots, correlation matrices)  
- **Business Interpretation** (connecting statistical results to social & policy insights)  

---

## 👥 Team Members (Group Project)  
- Vivan Doshi  
- Rohit Kumar  
- Jui Mathuria  
- Simran Chandak  
- Mansour Al-Mubarak  
- **Shahriar Rahman**

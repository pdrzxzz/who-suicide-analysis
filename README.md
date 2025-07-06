# 🌍 WHO Suicide Analysis  

**An Exploratory Data Analysis (EDA) of global suicide trends (1980–2015) using WHO data.**  
*Identifying patterns across countries, age groups, and demographics to understand risk factors and societal influences.*  

## 📌 **Key Features**  
- **Interactive visualizations** (Plotly) for dynamic exploration.  
- **Circular barplot** highlighting high-risk countries.  
- **Custom plotting function** (`plot_suicide_charts_interactive`) for comparative analysis.  
- **Country-specific deep dives** (Russia, USA, Japan, Brazil, Mexico).
  
## 🚀 **Explore the analysis**  
1. **Click here**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pdrzxzz/who-suicide-analysis/blob/main/who_suicides_analysis.ipynb)

## 📊 **Insights & Conclusions**  

### 🌍 **Global Trends**  
- Suicide rates **peaked in the 1990s** (especially in Russia) but declined steadily post-1994.  
- **Men die by suicide about 3× more often than women** across all age groups and years.  
- Adults aged **35–54** account for the majority of suicides globally,  as they represent a significant portion of the global population.

> ⚠️ **Data limitations:**
> *The dataset lacks information on important variables such as mental health status, socioeconomic level, access to healthcare, or quality of reporting systems. These limitations should be considered when interpreting results. Suicide may be **underreported or misclassified** in some countries.*

### 🌐 **Regional Patterns**  
- **Highest rates**: Europe and Asia (e.g., Russia, Japan, Ukraine).  
- **Lowest rates**: Africa, Caribbean, and Middle East (smaller populations and potential underreporting).  
- **Developed vs. Developing**: Economic prosperity doesn’t guarantee lower suicide risk—cultural and social factors play critical roles.  

### 🎯 **Policy Implications**  
- **Targeted mental health interventions** for high-risk groups (men, older adults).  
- **Community-based support systems** may mitigate risk in individualistic societies.
  
>  🗝️ **Key insight:**
> *Economic progress does not necessarily protect against suicide. Emotional well-being is deeply connected to social, cultural, and psychological factors.*  

---
- For the full analysis: check out the notebook.

## 🎓 **What I Learned**

* **Technical Win**: For exploratory work, interactivity changes everything — Plotly offers a far better experience than static Matplotlib.

* **Beyond Plotting: The Art of Asking Questions**:  
  * EDA starts with questions — not plots.  
  * It is not about creating visuals for the sake of it.  
  * It’s about asking clear, meaningful questions and using plots to explore or answer them.  
  
* **Analysis ≠ Description**:  
  * True analysis goes beyond simply describing patterns.
  * It seeks to understand why they exist and what they reveal about the real world.

* **Context matters**:  
  * Analysis requires the use of external knowledge or research in order to form hypotheses explaining patterns.  
  * For example, I incorporated external research on Russia’s socioeconomic collapse in the 1990s to interpret trends more meaningfully.

* **Complete Data Flow & Roles Overview**:  
  * Data Engineer → Prepares and pipelines the data.  
  * Data Analyst → Explores, visualizes, and finds insights.  
  * Data Scientist → Builds predictive or inferential models.  
  * ML Engineer → Turns models into deployable and scalable systems.  
  * Software Engineer → Builds applications that use or serve the data.  

  In this project, I worked as a Data Analyst. Since I’m still learning, I don’t yet know which path I’ll follow — but this project gave me a clear picture of what a data analyst actually does.

* **Beyond Numbers: Humans**:
  * This analysis reminded me of something essential: data is not the goal — people are.
  * Each number in this dataset represents a human being, not just a data point.
  Not a statistic. Not a case. A life.
  And that matters more than models, charts, or code.
  * What truly counts isn’t data, money, or progress — it’s human connection.
  And if this work doesn’t help us understand, support, or love people more deeply, then it loses its purpose.

## 📁 **Project Structure**  
```
who-suicide-analysis/  
├── who_suicides_analysis.ipynb  # Main analysis (EDA + plots)  
├── requirements.txt             # Dependencies  
└── README.md                    # Overview  
```

## 📦 **Dependencies**  
```python
numpy, pandas           # Data manipulation  
matplotlib, seaborn     # Static visualizations  
plotly                  # Interactive charts  
kagglehub               # Dataset access  
```

---
**May these insights contribute to meaningful conversations about mental health worldwide.** ❤️  

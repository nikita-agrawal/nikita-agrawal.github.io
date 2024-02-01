# About Me 
During my 4-year data science journey in consulting, technology product analytics and engineering research, I have cultivated a passion for delving into complex problems and crafting strategic and technical solutions that bring real value to businesses. I'm skilled in analyzing data and I thrive on fostering collaborative relationships across diverse teams. Please feel free to say hello at nikita24agrawal@gmail.com!

# Selected Projects

### >> Predicting unplanned hospitalizations <<        

**Company:** [Pandata](https://pandata.co/) 

**Problem:** Cancer centers aim to minimize unplanned hospital readmissions rates since they are associated with poor patient health outcomes, low quality of care and high costs. Existing readmissions prediction models do not work well on the cancer population. 

**Solution:** Using clinical, demographic and socio-economic data, several cancer-specific classification models were built to identify the top 74% of patients at risk of an unplanned 30-day readmission and provide personalized support, resulting in an estimate of $2.2 million cost savings per year. A dashboard was designed with visualizations of the leading factors contributing to individual patient risk score predictions to help clinical staff design targeted interventions. Explainable AI insights on the model risk predictions were added by computing the SHAP SHapley Additive exPlanations values. 

**Methods & Tools:** *xgboost, lightgbm, lasso, random forest, logistic regression, SHAP (SHapley Additive exPlanations), scikit-learn, mlr3, SQL, PowerBI*

[View Publication](https://ascopubs.org/doi/full/10.1200/CCI.22.00143?role=tab)

### >> Implementing KPIs to guide school zone decision making <<
  
**Company:** [Pandata](https://pandata.co/)

**Problem:** The architect team lacked an automated method to assess community impact when selecting schools for rebuilding and expansion. They faced challenges in quantifying impact at both student and neighborhood levels, relying on manual reviews and heuristics for each school, resulting in time-consuming evaluations. 

**Solution:** Addressing this issue, a semi-automated "what-if" dashboard tool and database were developed. This tool streamlined the evaluation of 170M planning scenarios, enabling simultaneous comparison of all schools in a given area. Key metrics like "median student commute time" and "number of highly rated schools within 5 miles" were incorporated. These metrics facilitated trade-off assessments among scenarios, supporting comprehensive decision-making regarding school prioritization for further investment.
 
**Methods & Tools:** *SQL, Azure, Python (dask, pandas, SQLAlchemy), PowerBI* 

### >> Experimentation to compare brain activity during various speech tasks << 
  
**Company:** [NYU Langone Health - Flinker Lab](https://flinkerlab.org/)

**Problem:** Before a patient undergoes left hemisphere brain surgery, the care team identifies speech-related brain regions to prevent post-surgery language issues. However, differing impacts of spontaneous versus prompted speech on brain activity remains uncertain. 

**Solution:** A series of experiments were designed and conducted to investigate this uncertainty. Unstructured speech and brain signals were first processed, and then a linear model was employed to predict brain activity from speech data. The findings unveiled heightened overall brain activity during prompted speech. However, spontaneous speech exhibited stronger brain encoding in two of the five specific brain regions studied.

**Methods & Tools:** *experimental design, hypothesis testing (ANOVA, Kruskal-Wallis, Wilcoxon rank sum, t-test), generalized linear modeling, MATLAB (mTRF toolbox), Python* 

_Data Blitz Talk & Poster presented at Cognitive Neuroscience Society 2020 Conference:_        
![](/assets/images/Agrawal_CNS_poster.png)

### >> Advanced analytics platform for product KPIs <<    
  
**Company:** [Medocity Inc.](https://www.medocity.com/platform/)

**Problem:** Various stakeholders at the telehealth app company from Client Success, Product Management, Marketing, Engineering, and Sales lacked a comprehensive means to monitor key performance indicators, assess application health, and efficiently manage client accounts. The absence of an internal integrated analytics platform hindered their ability to make informed decisions and track vital metrics effectively.

**Solution:** To address this challenge, an in-house analytics platform was developed and integrated seamlessly into the app interface. This platform facilitated real-time monitoring of KPIs related to user engagement, user behavior, and user satisfaction while enabling stakeholders to gauge app health and manage client accounts efficiently. Several training sessions on self-service BI were delivered to empower the team to comprehend and leverage data for decision-making, reducing ad-hoc reporting requests by 70%. 

**Methods & Tools:** *SQL, Tableau Server, data visualization, product roadmap planning, product requirements document creation, BI development and reporting*  

### >> Forecasting rental prices <<

**Company:** [Markerr](https://markerr.com/) *-  corporate partner for capstone at NYC Data Science Academy Bootcamp*  

**Problem:** The client, a commercial real estate platform, wanted to accurately forecast rental prices in the US with less than $100/month error using diverse alternative data sources in addition to the historical rent price data. 

**Solution:** Several time-series and supervised ML models were developed to accurately forecast rent price in 1000+ zip codes. Advanced data processing and feature engineering were applied to integrate Zillow Rent Index with alternative data (from Google Trends, the IRS, the ACS, public Bike Sharing datasets) in order to uncover valuable insights on rent price predictions.

**Methods & Tools:** *ARIMAX, Lasso, XGBoost, feature selection, feature engineering with time-lagged data, scikit-learn, Jupyter*   

[View Blog Write Up](https://nycdatascience.com/blog/student-works/data-driven-supervised-models-forecasting-u-s-rent-prices/) 

## :heavy_check_mark::heavy_check_mark: Predicting unplanned hospitalizations with explainable AI   

**Company:** [Pandata](https://pandata.co/)

**Problem:** Cancer centers aim to minimize unplanned hospital readmissions rates since they are associated with poor patient health outcomes, low quality of care and high costs. Existing readmissions prediction models do not work well on the cancer population. 

**Solution:** Using clinical, demographic and socio-economic data, several cancer-specific classification models were built to identify the top 74% of patients at risk of an unplanned 30-day readmission and provide personalized support, resulting in an estimate of $2.2 million cost savings per year. A dashboard was designed with visualizations of the leading factors contributing to individual patient risk score predictions to help clinical staff design targeted interventions. 

**Methods & Tools:** xgboost, lightgbm, lasso, random forest, logistic regression, SHAP, scikit-learn, mlr3, SQL, PowerBI.

[Related Publication](https://ascopubs.org/doi/full/10.1200/CCI.22.00143?role=tab)

## :heavy_check_mark: Implementing KPIs to guide school zone decision making  
  
**Company:** [Pandata](https://pandata.co/)

**Problem:** The architect team lacked an automated method to assess community impact when selecting schools for rebuilding and expansion. They faced challenges in quantifying impact at both student and neighborhood levels, relying on manual reviews and heuristics for each school, resulting in time-consuming evaluations. 

**Solution:** Addressing this issue, a semi-automated "what-if" dashboard tool and database were developed. This tool streamlined the evaluation of 170M planning scenarios, enabling simultaneous comparison of all schools in a given area. Key metrics like "median student commute time" and "number of highly rated schools within 5 miles" were incorporated. These metrics facilitated trade-off assessments among scenarios, supporting comprehensive decision-making regarding school prioritization for further investment.
 
**Methods & Tools:** SQL, Azure, Python (dask, pandas, SQLAlchemy), PowerBI. 

## :heavy_check_mark: Experimentation to compare brain activity for various speech tasks   
  
**Company:** [NYU Langone Health - Flinker Lab](https://flinkerlab.org/)

**Problem:** Before a patient undergoes left hemisphere brain surgery, the care team identifies speech-related brain regions to prevent post-surgery language issues. However, differing impacts of spontaneous versus prompted speech on brain activity remains uncertain. 

**Solution:** A series of experiments were designed and conducted to investigate this uncertainty. Unstructured speech and brain signals were first processed, and then a linear model was employed to predict brain activity from speech data. The findings unveiled heightened overall brain activity during prompted speech. However, spontaneous speech exhibited stronger brain encoding in two of the five specific brain regions studied.

**Methods & Tools:** experimental design, hypothesis testing (ANOVA, Kruskal-Wallis, Wilcoxon rank sum, t-test), generalized linear modeling, MATLAB (mTRF toolbox), Python  




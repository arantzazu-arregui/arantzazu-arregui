# Hi, I'm Arantzazu Arregui

I build machine learning and statistical models for real-world systems. I hold a Master of Management in Analytics from McGill University and a Chemical Engineering degree, and spent three years in process engineering and analytics at Procter & Gamble. My work covers surrogate modeling, causal inference, anomaly detection, and reproducible data pipelines.

## Core Skills
**Languages:** Python · SQL · R  
**Machine Learning & Statistics:** scikit-learn · PyTorch / GPyTorch · statsmodels · SHAP · Gaussian processes · causal inference  
**Data & Engineering:** pandas · NumPy · xarray · DuckDB · BigQuery (GCP) · pytest · Git  
**Optimization & BI:** Gurobi · Power BI (DAX)  

## Research

### Climate Model Emulation, Gomez Geodynamics & Climate Lab, McGill
Built Gaussian process emulators in GPyTorch as surrogates for the UVic climate model, returning predictions with uncertainty estimates in milliseconds instead of hours. Cut prediction error 64% to 87% against a linear pattern-scaling baseline. Co-author on a forthcoming paper; the code is not public yet.

## Featured Projects

### [Shipping Emissions Allocation](https://github.com/arantzazu-arregui/emissions-allocation)
Open-data reconstruction of Selin et al. (2021) on the national allocation of shipping CO2. A tested Python, DuckDB, and spatial SQL pipeline converts 140,000+ hourly ship records (2017 to 2024) into voyage-level emissions allocated by country. Found that one missing register field, installed engine power, drives most of the uncertainty (a **1.90x** difference in total emissions for the container ship).  
**Skills demonstrated:** data pipelines, spatial SQL, uncertainty analysis, testing and reproducibility

### [Kickstarter Success Prediction](https://github.com/arantzazu-arregui/kickstarter-project)
Built a predictive modeling workflow on 200k+ Kickstarter campaigns to estimate launch success under realistic forecasting conditions. Used a temporal train/test split and explicit leakage prevention to better reflect real-world deployment. A tuned Random Forest achieved **ROC-AUC of 0.81**, and SHAP analysis identified **funding goal** as the strongest predictor.  
**Skills demonstrated:** predictive modeling, feature engineering, model evaluation, business-focused interpretation

### [Yelp NLP Pipeline](https://github.com/arantzazu-arregui/nlp-yelp-project)
Created an end-to-end NLP pipeline on 100k Yelp reviews to analyze customer feedback at scale. Combined topic modeling, TF-IDF text classification, and aspect-level analysis to identify patterns in review content and sentiment. Built the workflow as a modular Python project with Makefile-driven execution for reproducibility and maintainability.  
**Skills demonstrated:** text analytics, classification, reproducible pipelines, insight extraction from unstructured data

### [Emergency Callbox Optimization](https://github.com/arantzazu-arregui/emergency-callbox-optimization)
Developed a mixed-integer optimization model in Gurobi to recommend emergency phone placement across McGill’s downtown campus. Extracted and structured spatial data from a campus PDF map, then optimized location choices to maximize safety coverage under budget constraints. The final model achieved **65.1% weighted coverage** at an estimated **$234,500 installation cost**.  
**Skills demonstrated:** optimization, geospatial data structuring, cost-coverage tradeoff analysis, decision support

### [Scin Data Modeling](https://github.com/wildg/Scin-Data-Modeling) *(contributor)*
Contributed to a team-based predictive modeling project by leading three core workstreams: **Feature Engineering**, **Semi-Supervised Learning Models**, and **LightGBM Model Development**. My contributions were tracked through the project board and focused on improving model performance and strengthening the overall workflow.  
**Skills demonstrated:** collaboration, model development, feature engineering, project ownership

## Let's Connect
[LinkedIn](https://linkedin.com/in/arantzazu-arreguigz) · aarregui97@gmail.com

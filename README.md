# Voice-Based-Health-Classification
Capstone project Voice-Based Health Classification

Capstone Project Description: 
Voice-Based Health Classification
Project Overview
In this capstone project, you will analyze a dataset containing audio-derived features (e.g., Mel filters, Fourier transformation) extracted from voice recordings of patients labeled as "Healthy" or "Unhealthy." The goal is to perform exploratory data analysis (EDA), clean the data, visualize insights in a Power BI dashboard, and build a predictive model to classify patients based on their health status.
Dataset Description
•	File: VowelA_High_latest.csv
•	Columns: 
o	Audio features: chroma_stft, rmse, spectral_centroid, spectral_bandwidth, rolloff, zero_crossing_rate, mfcc1 to mfcc20
o	Metadata: filename, ID, G (gender: 'm' or 'w'), A (age)
o	Target variable: label ("Healthy" or "Unhealthy")
•	Objective: Predict whether a patient is "Healthy" or "Unhealthy" based on audio features.
Deliverables
1.	EDA Python Notebook: 
o	Perform exploratory data analysis using Python (e.g., Pandas, Matplotlib, Seaborn).
o	Tasks: 
	Summarize dataset statistics (mean, median, etc.).
	Visualize distributions of features (histograms, box plots).
	Analyze correlations between features and the target variable.
	Identify missing values, outliers, or inconsistencies.
	Document insights and observations.
2.	Data Cleaning: 
o	Handle missing values, outliers, or noisy data.
o	Perform feature scaling/normalization if needed.
o	Encode categorical variables (e.g., gender).
o	Document cleaning steps in the EDA notebook.

3.	Power BI Dashboard (.pbix file): 
o	Create an interactive dashboard in Power BI to visualize key insights.
o	Include: 
	Visuals for feature distributions (e.g., histograms, bar charts).
	Relationships between features and health status.
	Filters for gender, age, or other relevant variables.
	Clear, professional layout with meaningful titles and descriptions.
4.	Predictive Model Python Notebook: 
o	Build a machine learning model to predict the label (Healthy/Unhealthy).
o	Tasks: 
	Split data into training and testing sets.
	Experiment with at least two algorithms (e.g., Decision Trees, Random Forest, XGBoost).
	Evaluate models using metrics like accuracy, precision, recall, and F1-score.
	Visualize model performance (e.g., confusion matrix, ROC curve).
5.	Detailed Report: 
o	Summarize the entire project in a professional report (PDF or Word).
o	Sections: 
	Introduction: Project goal and dataset description.
	EDA Findings: Key insights from data exploration.
	Data Cleaning: Steps taken to prepare the data.
	Power BI Dashboard: Description of visuals and their purpose.
	Predictive Model: Model selection, performance metrics, and results.
	Conclusion: Summary of findings and potential improvements.
o	Keep the report concise (5-7 pages) with clear visuals and explanations.
Guidelines
•	Use Python libraries like Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn for EDA and modeling.
•	Ensure the Power BI dashboard is user-friendly and visually appealing.
•	Document all code and processes clearly in the notebooks.
•	Submit all deliverables by [insert deadline].
Evaluation Criteria
•	EDA (30%): Depth of analysis, quality of visualizations, and clarity of insights.
•	Data Cleaning (15%): Effectiveness and documentation of cleaning steps.
•	Power BI Dashboard (20%): Clarity, interactivity, and relevance of visuals.
•	Predictive Model (25%): Model performance, evaluation, and optimization.
•	Report (10%): Structure, clarity, and completeness.
Submission Instructions
•	Upload all the files to your GitHub and provide your GitHub link.
Deadline: 9th November, 2025
Good luck, and showcase your data analytics skills in this comprehensive project!

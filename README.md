# Analysing cost of insurance claims post an unforeseen event

All State, a personal insurance company in the United States, is interested in leveraging data science to predict the severity and the cost of insurance claims post an unforeseen event.

- The datasets of the project is linked below
  
  [The Dataset](https://drive.google.com/drive/folders/1d5iFPajC16XnB0yvYx0HXKr9ftT0kYez?usp=drive_link)

The main aim of the Project was to perform Exploratory Data Analysis and Perform cleaning and perform predictions from the insurance Dataset.

Based on the Problem statement aanrget variable, we can conclude that we should use classification algorithm in this project.

Imported various Python libraries such as Pandas, NumPy, Seaborn and Matplotlib into Google Collab and Readed the insurance dataset using read_csv() function .we gone ahead in observing the dataset's unique values in every column separately.

While observing every column separately, we observed the values which are wrongly typed or in some values in which the values should be dropped, we cleaned the data accordingly.

while performing Exploratory data analysis, we performed univariate analysis, pie chart for categorical columns, correlation between data using heatmap and listed down the observations accordingly.

While performing Feauture engineering, we performed encoding using label encoder

While splitting the data according the vif factors previously checked, we selected the x and y columns accordingly, performed scaling using standard scalar and performed predictions using logistic regression, knn, decision tree and random forest.

- The Project's Data Cleaning part, EDA and Feauture Engineering part is Done in separate file Below.
  
  [The Project File - 1](https://github.com/ukishore33/Analysing-cost-of-insurance-claims-post-an-unforeseen-event/blob/main/Insurance_Claims_Unforeseen_Events.ipynb)
  
- The Project's Machine Learning part is Done in separate file Below.
  
  [The Project File - 2](https://github.com/ukishore33/Analysing-cost-of-insurance-claims-post-an-unforeseen-event/blob/main/Insurance_Claims_Unforeseen_Events_ML_Part.ipynb)

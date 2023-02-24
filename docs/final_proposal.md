# Water Quality Predection
Water quality parameters include chemical, physical, and biological properties and can be tested or monitored based on the desired water parameters of concern. Parameters that are frequently sampled or monitored for water quality include temperature, dissolved oxygen, pH, conductivity, ORP, and turbidity. However water monitoring may also include measuring total algae, ISEs (ammonia, nitrate, chloride), or laboratory parameters such as BOD, titration, or TOC

# ![image](https://user-images.githubusercontent.com/124104312/221208395-31d5ddc2-23f9-45f5-865d-4569380426bd.png)

## Explainning the project
putting machine learning methods to use to build a prediction of water quality. Using some factors, such as the Ph level, conductivity, hardness, etc., this technique forecasts if the water is fine to consume or not.
## About Data
The dataset considered for this project is taken from Kaggle dataset. Link is given below
https://www.kaggle.com/adityakadiwal/water-potability

Dataset consists of 3276 records with 10 column of which 9 are input variables and 'potability' is the output variable.

ppm: parts per million
μg/L: microgram per litre
mg/L: milligram per litre

Column description:

1. ph: pH of 1. water (0 to 14).
2. Hardness: Capacity of water to precipitate soap in mg/L.
3. Solids: Total dissolved solids in ppm.
4. Chloramines: Amount of Chloramines in ppm.
5. Sulfate: Amount of Sulfates dissolved in mg/L.
6. Conductivity: Electrical conductivity of water in μS/cm.
7. Organic_carbon: Amount of organic carbon in ppm.
8. Trihalomethanes: Amount of Trihalomethanes in μg/L.
9. Turbidity: Measure of light emiting property of water in NTU.
10. Potability: Indicates if water is safe for human consumption. Potable is 1 and not potable is 0.
![image](https://user-images.githubusercontent.com/124104312/221211618-587cf360-56bc-4081-8a13-b8124fa90145.png)
## Model Architecture
To build a machine learning model for water potability dataset, steps:
1.	Load the data: Start by loading the water potability dataset, which is in CSV format, into a Pandas DataFrame.
2.	Exploratory data analysis: Conduct exploratory data analysis (EDA) to get an understanding of the dataset. This can include checking for missing values, analyzing the distribution of features, and looking for correlations between features.
3.	Data pre-processing: Pre-process the data by handling missing values, converting categorical variables to numerical variables, and scaling the data if necessary.
4.	Feature selection: Select the most relevant features for your machine learning model. This can be done by analyzing feature importance or conducting feature selection techniques such as recursive feature elimination.
5.	Splitting the dataset: Split the dataset into training and testing sets. This will allow to train  model on a subset of the data and evaluate its performance on another subset.
6.	Building a model: Choose an appropriate machine learning algorithm and build a model. can experiment with different algorithms such as logistic regression, decision trees, random forests, or neural networks.
7.	Training the model: Train the machine learning model on the training dataset. This involves fitting the model to the data and optimizing the model's parameters.
8.	Evaluating the model: Evaluate the performance of the machine learning model on the testing dataset. can use metrics such as accuracy, precision, recall, and F1 score to evaluate the performance of the model.
9.	Tuning the model: Tune the hyperparameters of the machine learning model to optimize its performance.
10.	Deploying the model: Once aim are satisfied with the performance of the machine learning model, can deploy it in a production environment( i am going to use Streamlit)

![image](https://user-images.githubusercontent.com/124104312/221227805-03d608b5-bd3c-41e7-94be-f61723d8069a.png)







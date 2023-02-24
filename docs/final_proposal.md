# Water Quality Predection
Water quality parameters include chemical, physical, and biological properties and can be tested or monitored based on the desired water parameters of concern. Parameters that are frequently sampled or monitored for water quality include temperature, dissolved oxygen, pH, conductivity, ORP, and turbidity. However water monitoring may also include measuring total algae, ISEs (ammonia, nitrate, chloride), or laboratory parameters such as BOD, titration, or TOC

# ![image](https://user-images.githubusercontent.com/124104312/221208395-31d5ddc2-23f9-45f5-865d-4569380426bd.png)

## Explainning the project
putting machine learning methods to use to build a prediction of water quality. Using some factors, such as the Ph level, conductivity, hardness, etc., this technique forecasts if the water is fine to consume or not.
## About Data
The dataset considered for this project is taken from Kaggle dataset. Link is given below
https://www.kaggle.com/adityakadiwal/water-potability

Dataset consists of **3276 records** with **10 column** of which 9 are input variables and 'potability' is the output variable.

ppm: parts per million
μg/L: microgram per litre
mg/L: milligram per litre

### Column description:

**1. ph:** pH of 1. water (0 to 14).
   When assessing the acid-base balance of water, PH is a key factor. Moreover, it shows if the water is acidic or alkaline. The maximum pH allowed range, according to WHO, is between 6.5 and 8.5. The current investigation's ranges fell between 6.52 and 6.83, which is within WHO criteria.
   
**2. Hardness:** Capacity of water to precipitate soap in mg/L.
   Salts made of calcium and magnesium are the main culprits in hardness. These salts are released by the geologic formations that water passes through. How long water is exposed to a hardness-producing substance influences how hard the water is when it is in its raw state. The ability of water to form soap due to calcium and magnesium precipitation was the original definition of hardness.
   
**3. Solids:** Total dissolved solids in ppm.
   Many inorganic and some organic minerals or salts, including potassium, calcium, sodium, bicarbonates, chlorides, magnesium, sulfates, and others, can be dissolved by water. These minerals gave the water an undesirable flavor and muted color. This is a crucial variable while using water. Water with a high TDS rating is one that has a high mineral content. The recommended TDS level for drinking purposes is 500 mg/l, with a maximum limit of 1000 mg/l.
   
**4. Chloramines:** Amount of Chloramines in ppm.
   The two main disinfectants utilized in public water systems are chlorine and chloramine. When ammonia is added to chlorine to purify drinking water, chloramines are most frequently generated. Drinking water can include up to 4 mg/L of chlorine (or 4 ppm), which is regarded as a safe quantity.
   
**5. Sulfate:** Amount of Sulfates dissolved in mg/L.
   Sulfates are organic compounds that are naturally present in rocks, soil, and minerals. They can be found in the surrounding air, groundwater, vegetation, and food. Sulfate is mostly used in the chemical industry for commercial purposes. The amount of sulfate in saltwater is around 2,700 mg/L. The majority of freshwater sources have values between 3 and 30 mg/L, while certain regions have substantially higher levels (1000 mg/L).
   
**6. Conductivity:** Electrical conductivity of water in μS/cm.
   Clean water is a good insulator rather than a good conductor of electrical current. The electrical conductivity of water is improved by an increase in ion concentration. The electrical conductivity of water is typically determined by the amount of dissolved particles present. The ability of a solution to convey current through its ionic process is measured by electrical conductivity (EC). According to WHO guidelines, the EC value shouldn't be more than 400 S/cm.
   
**7. Organic_carbon:** Amount of organic carbon in ppm.
   Total Organic Carbon (TOC) in source waters comes from decaying natural organic matter (NOM) as well as synthetic sources. TOC is a measure of the total amount of carbon in organic compounds in pure water. According to US EPA < 2 mg/L as TOC in treated / drinking water, and < 4 mg/Lit in source water which is use for treatment.
   
**8. Trihalomethanes:** Amount of Trihalomethanes in μg/L.
   THMs are chemicals which may be found in water treated with chlorine. The concentration of THMs in drinking water varies according to the level of organic material in the water, the amount of chlorine required to treat the water, and the temperature of the water that is being treated. THM levels up to 80 ppm is considered safe in drinking water.
   
**9. Turbidity:** Measure of light emiting property of water in NTU.
   The turbidity of water depends on the quantity of solid matter present in the suspended state. It is a measure of light emitting properties of water and the test is used to indicate the quality of waste discharge with respect to colloidal matter. The mean turbidity value obtained for Wondo Genet Campus (0.98 NTU) is lower than the WHO recommended value of 5.00 NTU.
   
**10. Potability:** Indicates if water is safe for human consumption. Potable is 1 and not potable is 0.

![image](https://user-images.githubusercontent.com/124104312/221211618-587cf360-56bc-4081-8a13-b8124fa90145.png)
## Model Architecture
To build a machine learning model for water potability dataset, steps:
**1.	Load the data:** Start by loading the water potability dataset, which is in CSV format, into a Pandas DataFrame.

**2.	Exploratory data analysis:** Conduct exploratory data analysis (EDA) to get an understanding of the dataset. This can include checking for missing values, analyzing the distribution of features, and looking for correlations between features.

**3.	Data pre-processing:** Pre-process the data by handling missing values, converting categorical variables to numerical variables, and scaling the data if necessary.

**4.	Feature selection:** Select the most relevant features for your machine learning model. This can be done by analyzing feature importance or conducting feature selection techniques such as recursive feature elimination.

**5.	Splitting the dataset:** Split the dataset into training and testing sets. This will allow to train  model on a subset of the data and evaluate its performance on another subset.

**6.	Building a model:** Choose an appropriate machine learning algorithm and build a model. can experiment with different algorithms such as logistic regression, decision trees, random forests, or neural networks.

**7.	Training the model:** Train the machine learning model on the training dataset. This involves fitting the model to the data and optimizing the model's parameters.

**8.	Evaluating the model:** Evaluate the performance of the machine learning model on the testing dataset. can use metrics such as accuracy, precision, recall, and F1 score to evaluate the performance of the model.

**9.	Tuning the model:** Tune the hyperparameters of the machine learning model to optimize its performance.

**10.	Deploying the model:** Once aim are satisfied with the performance of the machine learning model, can deploy it in a production environment( i am going to use Streamlit)

![image](https://user-images.githubusercontent.com/124104312/221227805-03d608b5-bd3c-41e7-94be-f61723d8069a.png)







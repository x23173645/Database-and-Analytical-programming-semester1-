# Database-and-Analytical-programming-semester1-
Data Extraction: You previously extracted data of certain medical programs via APIs from a government website for ease and stored this data in both MongoDB and PostgreSQL databases.
Data Cleaning: After extraction, the data cleaned to maintain its efficiency and effectiveness, and some techniques use like KNNImputer for imputation of missing values.
Data Visualization: You need multiple techniques and libraries like Matplotlib, Seaborn, Plotly, and Folium to visualize the data you extracted. Exploratory Data Analysis was performed on the individual datasets that included respective readmission rates, surgery complications, rates of mortality, and overall patient care.
Integration and Analysis: Integration was further conducted combining all factors to establish the relationship of each on the payment that the Medicare recipients pay.
Modeling: Initially, Logistic Regression was performed on the basis of segmentation and classification, but it was found the class imbalance in this model, so respective SMOTE technique was used for upsampling. Recursive Feature Elimination was used for feature selection.
Finally, the classification as a logistic regression classifier was at 68% accuracy for the test set which is further helpful to increase the precision for identifying payment.
Key Predictors: You data model analysis found that the key predictors included the complications that arose during hip/ knee surgery, excess readmissions for a heart attack, and the total HAC score, representing a relationship between the quality of care and the payment issue .
Data Sources: The project was completely based on federal government programs who are including the Hospital-Acquired Condition Reduction Program , the Hospital Readmissions Reduction Program, and the Hospital Value-Based Purchasing program choosing an ideal dataset for training the data.
 
 

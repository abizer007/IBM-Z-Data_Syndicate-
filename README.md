# IBM Z Data_Syndicate: Supply Chain Disurtion Analysis Model
Data Syndicate ONL 169
Team Members:-

Abizer Masavi(Team Leader)

Swapnil Pal

Shreyesh Nikam

Subhankar Soumya Ranasingh

Arzaan Mulla

Subham Mohapatra

Problem statement :- In today’s interconnected world, supply chain disruptions caused by geopolitical tensions and extreme weather events pose significant challenges to global stability and public welfare. These disruptions lead to severe shortages of essential goods, such as food, medical supplies, and critical infrastructure components, adversely affecting vulnerable populations and industries alike. Rising costs and limited access to resources further exacerbate food insecurity, hinder healthcare services, and fuel broader economic instability, creating ripple effects across communities.
Moreover, traditional supply chain systems often lack transparency, adaptability, and predictive capabilities, making it difficult to respond quickly and effectively to sudden disruptions. Addressing these issues requires robust, scalable, and secure technological solutions tailored to global supply chain challenges.
Our project leverages the power of IBM zSystems, incorporating key technologies such as IBM’s z/OS, DB2, Watson AI, and Snap ML to build a highly resilient supply chain solution. Using Watson X, we will deploy machine learning models for real-time predictive analytics to forecast potential disruptions and optimize resource allocation strategies. Additionally, blockchain technology via Hyperledger Fabric on IBM z will ensure secure, end-to-end transparency across the supply chain. IBM Cloud Pak for Data will facilitate data-driven decision-making, while IBM’s Sysplex architecture provides high availability and scalability for critical supply chain operations.
This framework ensures equitable access to essential goods, reduces disruptions, and builds long-term resilience


Solution - 
1. Data Loading and Cleaning
Explanation: The first step involves loading FAO Food Price Index data using pandas and ensuring that the critical 'value' column is present. This is where we check for missing or corrupted data and ensure that all relevant features, such as the year and value, are in the correct format for analysis.
IBM zLinux One: This is where IBM zLinux One’s robust processing power comes in handy. The platform efficiently handles large datasets, ensuring quick loading and cleaning without latency issues.
Output Example: A cleaned dataset ready for further processing.
2. Data Visualization
Explanation: We use data visualization techniques like correlation heatmaps and distribution plots to better understand the relationships between variables. This helps identify patterns or anomalies in food prices, which could be early indicators of supply chain disruptions.
IBM Packages: Utilizing Matplotlib and Seaborn libraries, this visualization step takes advantage of Watson Studio's integration with zSystems to provide high-performance graphics.
Output Example: Heatmaps showing the correlation between food price indices and other features.

![image_2024-10-20_122330298](https://github.com/user-attachments/assets/883173bd-be4d-4fc5-89d2-f1e273718039)

![image](https://github.com/user-attachments/assets/141d213c-aa31-4435-92ed-793999d571cd)


4. Feature Engineering
Explanation: Feature engineering plays a key role in model performance. Here, we standardize the 'value' column to create a new feature, 'value_scaled', and introduce a binary variable indicating whether the data belongs to recent years (post-2020). These engineered features help improve model predictions.
Watson AI Integration: Watson Studio enhances this step by providing additional computational power to quickly standardize and engineer features.
Output Example: A dataset with new features like 'value_scaled' and 'is_recent'.
5. Model Training and Comparison
Explanation: Multiple machine learning models, including XGBoost, Logistic Regression, Random Forest, and SVM, are trained and compared. Each model's performance is evaluated using classification reports, confusion matrices, and cross-validation scores to ensure the most accurate model is chosen.
IBM’s Snap ML: The Snap ML package, optimized for z/OS, accelerates the training process, allowing models like XGBoost to run faster and more efficiently on large datasets.
Output Example: Comparison tables and reports showing the performance of various models.
6. Hyperparameter Tuning
Explanation: To further enhance the model, hyperparameter tuning is performed on the XGBoost model using a grid search. This ensures that the model is optimized for maximum accuracy in predicting disruptions.
IBM Cloud Pak for Data: This step uses IBM’s Cloud Pak to streamline the tuning process, ensuring that all parameters are tested efficiently on the zSystems infrastructure.
Output Example: The best model configuration and its accuracy score.
7. Feature Importance Analysis
Explanation: After the model is trained, we analyze the feature importance using XGBoost’s in-built functionality. This helps identify which variables are most influential in predicting disruptions, providing valuable insights into the factors affecting supply chain stability.
Output Example: A feature importance graph showing the top features.
8. Ensemble Learning
Explanation: To further improve model performance, we implement an ensemble model that combines XGBoost, Logistic Regression, Random Forest, and SVM classifiers. This ensemble model increases prediction accuracy by leveraging the strengths of multiple algorithms.
Sysplex Architecture: The ensemble model benefits from the Sysplex architecture, which provides the high availability and processing capacity required to handle multiple models simultaneously.
Output Example: Ensemble model classification report and performance metrics.
9. Final Evaluation
Explanation: Finally, the best-performing model is evaluated on the test set. Classification reports, confusion matrices, and ROC curves are used to assess its performance, ensuring that the model is robust and reliable for predicting real-world supply chain disruptions.
Output Example: Final classification reports, ROC curve, and confusion matrices for the best model.

![image](https://github.com/user-attachments/assets/70f59350-8fcb-45c4-b803-2737fde40cde)

Additional Sections for Repository:
Challenges Faced: Include a section describing challenges such as data quality, model optimization, and integration with IBM’s zSystems, and how these were addressed.
Learnings and Insights: Highlight both the technical and soft skills learned during the project, such as teamwork, problem-solving, and data modeling on a large scale.
IBM zSystems and Linux One Platform Use:
Platform Integration: Throughout the project, IBM zSystems played a critical role by ensuring data security, high availability, and scalability. The project leveraged the computational power of IBM’s zLinux One for data processing and training complex machine learning models.
Packages Used:
Watson Studio: For data import, cleaning, and model training.
Snap ML: To accelerate the machine learning process, optimizing large datasets.
DB2: For secure data storage and retrieval.
Hyperledger Fabric: For blockchain integration, ensuring transparent and secure data tracking across the supply chain.

![image_2024-10-20_122133114](https://github.com/user-attachments/assets/faed67c5-8cfc-475f-9d89-6b251b53d313)

![image](https://github.com/user-attachments/assets/1447e036-68f2-4388-9058-941bf423b0cf)


Wow Factors - 
1) Innovative Feature Engineering: The project utilizes advanced feature engineering techniques, such as creating standardized values and binary indicators, to enhance model performance, demonstrating a deep understanding of the dataset.
2) Diverse Model Selection: The implementation of multiple machine learning algorithms, including XGBoost, Random Forest, and SVM, showcases a comprehensive approach to model selection and an understanding of their strengths and weaknesses.
3) Hyperparameter Optimization: The inclusion of hyperparameter tuning for the XGBoost model demonstrates a commitment to maximizing model accuracy and performance, leading to more reliable predictions.
4) Ensemble Learning: The use of an ensemble model that combines multiple classifiers highlights a sophisticated understanding of machine learning techniques and their ability to improve predictive performance through collaboration.
5) Data Visualization Techniques: The integration of correlation heatmaps and distribution plots not only aids in understanding the data but also enhances the presentation, making complex information more accessible to stakeholders.
6) ROC Curve Analysis: The addition of ROC curve analysis to evaluate model performance offers a visually compelling way to communicate the effectiveness of your models, demonstrating a focus on interpretability and usability.
7) Real-World Relevance: The project addresses a pressing global issue—supply chain disruptions and food security—showcasing its potential real-world impact and relevance in today's context.
8) Robust Evaluation Metrics: The thorough evaluation of models using classification reports and confusion matrices illustrates a detailed approach to model assessment, ensuring that the best model is chosen for deployment.

Learnings - Technical:

1. IBM Z and supply chain disruption analysis
2. Data preprocessing, visualization, and modeling
3. Machine learning integration

Soft Skills:

1. Teamwork under pressure
2. Time management and communication
3. Adaptability and resilience

Challenges:

1. Data quality and cleaning
2. Model optimization
3. Integration and debugging

Takeaways:

1. Pre-event prep
2. Clear goals and communication
3. Flexibility and teamwork

Personal Growth:

1. Enhanced problem-solving
2. Improved coding efficiency
3. Boosted confidence

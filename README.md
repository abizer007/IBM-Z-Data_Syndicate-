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


Solution - The Python code I created implements a machine learning pipeline to analyze the FAO food price index data and predict supply chain disruptions. It starts by loading and cleaning the dataset, ensuring that the 'value' column is present and creating additional features such as a standardized value and a binary indicator for recent years. Data visualization is included to better understand the data through correlation heatmaps and distribution plots. I then set up a dummy target variable for supply chain disruption and split the dataset into training and testing sets. I trained various machine learning models, including XGBoost, Logistic Regression, Random Forest, and SVM, and compared their performance using classification reports, confusion matrices, and cross-validation scores. I also performed hyperparameter tuning for the XGBoost model to enhance its performance. Additionally, I implemented an ensemble model that combines multiple classifiers for improved accuracy. To evaluate the models further, I included ROC curve analysis to visualize their performance metrics. Overall, this code showcases effective feature engineering, model comparison, and evaluation techniques, providing a strong framework for addressing supply chain disruptions and analyzing food security issues.

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

**Preprocessing**

The dataset was prepared for modeling by removing non-informative identifiers such as ID and Unnamed: 0, and evaluating missing values across all features. Key variables included Customer Type, Type of Travel, Class, Flight Distance, Departure Delay, Arrival Delay, and service-related ratings. Missing values were assessed and handled to ensure compatibility with machine learning models. Categorical variables were encoded, and numerical features were standardized where appropriate to support model performance.

**Analysis**

The analysis focused on predicting customer satisfaction (satisfied vs. dissatisfied) using supervised learning techniques. A Logistic Regression model was implemented as a baseline to evaluate linear relationships between customer characteristics, delays, and satisfaction outcomes. Model performance was assessed using metrics such as accuracy, confusion matrices, and classification reports. A Decision Tree classifier was then applied to capture non-linear relationships and interactions between variables, particularly categorical features like Customer Type and Type of Travel. Model complexity and potential overfitting were evaluated through training vs. testing performance comparisons.

**Results**

The results showed that flight delays, customer type, and travel characteristics were among the most influential factors in predicting customer satisfaction. The Decision Tree model slightly outperformed Logistic Regression, suggesting that non-linear patterns and feature interactions play a significant role in satisfaction outcomes. Overall, the project demonstrates how data preprocessing, feature handling, and comparative modeling can be used to derive actionable insights into customer experience drivers.

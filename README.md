##  Project: Predicting Customer Subscription Using Classification Models

In this project, I developed a classification model to predict whether a client will subscribe to a term deposit based on data collected from direct marketing campaigns. The dataset, provided by a Portuguese banking institution, contains rich customer information, including demographics, financial status, and campaign interaction history.

This type of predictive modeling is incredibly valuable in the financial services industry. It enables organizations to identify high-potential clients, personalize outreach strategies, and increase the efficiency of marketing efforts — ultimately improving customer acquisition while reducing costs.

---

###  Dataset Description

The dataset includes **numerical and categorical** variables for over 40,000 client records, with features such as:

- **Demographics**: Age, job type, marital status, education
- **Financial Information**: Default status, balance, housing and personal loans
- **Marketing Campaign Details**: Contact method, last contact duration, campaign frequency
- **Outcome Variables**: Past campaign results and the final target — whether the client subscribed (`y`)

 Source: UCI Machine Learning Repository (Bank Marketing Dataset)

---

###  Approach

1. **Data Preprocessing**:  
   - Encoded categorical variables (e.g., job, education)  
   - Scaled numeric features to ensure model stability  
   - Removed or analyzed features like `duration` to prevent data leakage

2. **Model Development**:  
   - Split data into training and testing sets  
   - Trained models including **Logistic Regression** and **Random Forest Classifier**  
   - Applied **cross-validation** to avoid overfitting

3. **Model Evaluation**:  
   - Used metrics such as **accuracy**, **precision**, **recall**, and **F1-score**  
   - Analyzed the confusion matrix to evaluate true/false positives and negatives  
   - Selected the best-performing model based on business context (e.g., minimizing false positives)

---

###  Outcome

By the end of the project, I successfully built and validated a classification model that can effectively predict client subscription behavior. This project demonstrates my ability to handle real-world datasets, apply appropriate machine learning techniques, and extract actionable insights for decision-making in a business environment.

---

### 📌 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Matplotlib / Seaborn (for data visualization)

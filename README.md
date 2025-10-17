# SCT_DS_Task3_BankMarketing
#Skill Craft Technology Internship — Task 3
*Bank Marketing Dataset — Decision Tree Classifier using Python*
This task focuses on analyzing customer data from a Portuguese bank’s marketing campaign to predict whether a client will subscribe to a term deposit. The project includes data cleaning, label encoding, model training, and decision tree visualization.
# Folder Structure
- `task3_bank_marketing_eda/`
  - `data/`
    - `bank-full.csv`: Raw dataset with customer attributes
  - `images/`
    - `task3_1.png`: Decision tree visualization
    - `task3_2.png`: Additional chart or insight
  - `notebook/`
    - `skilltask3(sk).ipynb`: Jupyter Notebook with full workflow
#  Dataset Overview
- *Source*: Portuguese bank marketing campaign
- *Target column*: `y` (whether client subscribed to a term deposit)
- *Features*: Age, job, marital status, education, balance, housing, loan, contact method, campaign metrics, and previous outcomes
#  Workflow Summary
1. *Data Cleaning*:
   - Standardized column names
   - Encoded categorical variables using `LabelEncoder`
2. *Model Building*:
   - Split data into training and test sets
   - Trained a `DecisionTreeClassifier` with max depth of 5
3. *Evaluation*:
   - Printed accuracy and classification report
   - Visualized the decision tree using `plot_tree`
# Visuals
# Decision Tree Classifier  
![Decision Tree](/images/task3_1.png)
# Additional Insight  
![Chart](/images/task3_2.png)
#  Key Insight
The decision tree highlights key features like `duration`, `poutcome`, and `contact` as strong predictors of client subscription. The model provides interpretable rules for campaign targeting.
#  Tools Used
- Python (Pandas, scikit-learn, Matplotlib)
- Jupyter Notebook
- GitHub for version control

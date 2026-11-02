# Constructing-Models-to-Predict-Product-Failures
(Predictive modeling, exploratory/ descriptive analysis, data visualization, R, data stratification, PowerPoint, Word)
## Project Description
This course project had two phases:
- Phase 1: conduct a thorough exploratory/ descriptive analysis of the dataset, with the assumption that the target audience is non-technical decision makers. Deliverable 1 is a PowerPoint presentation summarizing phase 1 findings, including indicating which variables may be strong predictors of the "failure" variable. Deliverable 2 is a knitted Word document of the Phase 1 R work.
- Phase 1: build multiple predictive models that predict the variable "failure" using training/ testing splits, k-fold cross-validation, etc. Deliverable 1 is a PowerPoint presentation summarizing phase 1 findings, even weak ones. Deliverable 2 is a knitted Word document of Phase 2 R work. Deliverable 3 is a Kaggle submission of the test.csv file of each model you build to enter the Kaggle competition for the dataset.
## Phase 1 Key Findings
The dataset was provided from Kaggle. Exploratory analysis was performed using R to identify which variables in the given dataset may contribute to product failure of a fictional product called Super Soaker, a mat that soaks up moisture. Such a product could prove useful in a typical manufacturing or other facility setting. 

Outliers in the dataset were cleaned by row-wise deletion, and missing data was cleaned by imputation. Data was split 70/30 into train and test data. 

Few variables stood out as strong predictors of product failure after the exploratory analysis was conducted, but the potential predictors were culled from a total of 25 variables in the given dataset, including the variable of interest, to 8 variables to explore as potential predictors of the variable "failure". These potential predictor variables for product failure were identified to be the variables measurement_2, measurement_5, measurement_6, measurement_8, measurement_17, attribute_3, loading, and product_codeA. 

A summary of this process and these findings is described in the PowerPoint presentation for Phase 1 of the project, and the knitted Word document containing R code, below:
### Phase 1 Files
[Phase 1 Summary](./Project_Ph1_VariableSelection.pdf)

[R Code](./BAN502_VariableSelect.pdf)

<img width="1227" height="691" alt="image" src="https://github.com/user-attachments/assets/eb89da5e-6636-4304-af1b-8f051589b67b" />

<img width="1226" height="688" alt="image" src="https://github.com/user-attachments/assets/506a0bc7-e119-4010-aecc-43d51e375ec5" />

<img width="1225" height="689" alt="image" src="https://github.com/user-attachments/assets/4585a4c4-45ee-4796-894c-2e6217274b98" />

<img width="1227" height="690" alt="image" src="https://github.com/user-attachments/assets/3d699f07-5e42-492a-901a-9ddfc3ec532d" />

<img width="1226" height="688" alt="image" src="https://github.com/user-attachments/assets/4ddb047b-1672-451a-87d4-fbc0bfde08a9" />

<img width="1227" height="691" alt="image" src="https://github.com/user-attachments/assets/37487482-a0b2-466d-bf72-78397d0a2ca3" />

<img width="1228" height="689" alt="image" src="https://github.com/user-attachments/assets/6c431c94-6af3-4c93-b684-f1e33a74c932" />


## Phase 2 Key Findings and Project Conclusion
For Phase 2 of the project, the task was to build multiple predictive models using training/ testing splits, k-fold cross-validation, and other means to predict failure of the fictional Super Soaker product. Variations of different models were constructed to aid in predictions, to include:
- Logistic Regression
- Classification Tree
- Random Forest
- XGBoost
- Neural Network
- Ensemble

A summary table of model performance is provided below:

<img width="766" height="364" alt="image" src="https://github.com/user-attachments/assets/2877264f-0068-4b61-87ba-475d903cb358" />

Random Forests were the only models achieving reasonable accuracy, which reflects their strength in capturing nonlinear relationships among predictor variables,, but they were still subject to significant overfitting, as indicated by substantial train-test set gaps. All models struggled with the imbalanced failure variable outcome, 79% nonfailure, 21% failure, which resulted in low sensitivity. Therefore, no model demonstrated minority class detection, which limited the practical use for identifying true failure cases.

### Phase 2 Files
[Phase 2 Summary](./Project_Ph2_Models.pdf)

[R Code Classification Tree Model](./BAN502_ClassTree.pdf)

[R Code Classification Tree2 Model](./BAN502_ClassTree2.pdf)

[R Code Classification Tree3 Model](./BAN502_ClassTree3.pdf)

[R Code Classification Tree4 Model](./BAN502_ClassTree4.pdf)

[R Code Classification Tree Select Variables Model](./BAN502_ClassTreeSelect.pdf)

[R Code Ensemble Model](./BAN502_Ensemble.pdf)

[R Code Logistic Regression Model](./BAN502_Logit.pdf)

[R Code Logistic Regression2 Model](./BAN502_Logit2.pdf)

[R Code Logistic Regression3 Model](./BAN502_Logit3.pdf)

[R Code Logistic Regression4 Model](./BAN502_Logit4.pdf)

[R Code Neural Network Model](./BAN502_NNetwork.pdf)

[R Code Neural Network2 Model](./BAN502_NNetwork2.pdf)

[R Code Random Forest2 Model](./BAN502_RForest2.pdf)

[R Code Random Forest3 Model](./BAN502_RForest3.pdf)

[R Code Random Forest4 Model](./BAN502_RForest4.pdf)

[R Code Random Forest4 App Model](./BAN502_RForest4_App.pdf)

[R Code Random Forest Tuned Model](./BAN502_RForestTuned.pdf)

[R Code Random Forest Tuned2 Model](./BAN502_RForestTuned2.pdf)

[R Code Random Forest Tuned2 App Model](./BAN502_RForestTuned2_App.pdf)

[R Code Random Forest Tuned3 Model](./BAN502_RForestTuned3.pdf)

[R Code Random Forest Tuned4 Model](./BAN502_RForestTuned4.pdf)

[R Code XG Boost Tuned Model](./BAN502_XGBTuned.pdf)

[R Code XG Boost Tuned2 Model](./BAN502_XGBTuned2.pdf)

[R Code XG Boost Tuned3 Model](./BAN502_XGBTuned3.pdf)

<img width="1229" height="691" alt="image" src="https://github.com/user-attachments/assets/ab712867-0d84-439a-a69a-645983ce4e25" />

<img width="1227" height="692" alt="image" src="https://github.com/user-attachments/assets/8a443ef6-1a05-4438-8251-bc0aff6a75e3" />

<img width="1228" height="690" alt="image" src="https://github.com/user-attachments/assets/59995f3c-ab40-4ab3-8dc5-f20bbac88158" />

<img width="1227" height="692" alt="image" src="https://github.com/user-attachments/assets/91f072d0-1325-4fba-9b4e-e13154621748" />

<img width="1226" height="691" alt="image" src="https://github.com/user-attachments/assets/903facfc-27b3-45eb-aa02-758222cbb89f" />

<img width="1228" height="689" alt="image" src="https://github.com/user-attachments/assets/d5925ddc-6c4f-495b-8b26-95982a2fa2fd" />

<img width="1229" height="692" alt="image" src="https://github.com/user-attachments/assets/799f9eb1-66d5-4f82-a9f3-192a4b98c887" />








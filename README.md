# Constructing-Models-to-Predict-Product-Failures
(Predictive modeling, exploratory/ descriptive analysis, data visualization, R, data stratification, PowerPoint, Word)
## Project Description
This course project had two phases:
- Phase 1: conduct a thorough exploratory/ descriptive analysis of the dataset, with the assumption that the target audience is non-technical decision makers. Deliverable 1 is a PowerPoint presentation summarizing phase 1 findings, including indicating which variables may be strong predictors of the "failure" variable. Deliverable 2 is a knitted Word document of the Phase 1 R work.
- Phase 1: build multiple predictive models that predict the variable "failure" using training/ testing splits, k-fold cross-validation, etc. Deliverable 1 is a PowerPoint presentation summarizing phase 1 findings, even weak ones. Deliverable 2 is a knitted Word document of Phase 2 R work. Deliverable 3 is a Kaggle submission of the test.csv file of each model you build to enter the Kaggle competition for the dataset.
## Phase 1 Key Findings
The dataset was provided from Kaggle. Exploratory analysis was performed using R to identify which variables in the given dataset may contribute to product failure of a fictional product called Super Soaker, a mat that soaks up moisture. Such a product could prove useful in a typical manufacturing or other facility setting. Outliers in the dataset were cleaned by row-wise deletion, and missing data was cleaned by imputation. Data was split 70/30 into train and test data. Few variables stood out after the exploratory analysis was conducted, but the potential predictors were culled from a total of 25 variables in the given dataset, including the variable of interest, to 8 variables to explore as potential predictors of the variable "failure". These potential predictor variables for product failure were identified to be the variables measurement_2, measurement_5, measurement_6, measurement_8, measurement_17, attribute_3, loading, and product_codeA. A summary of this process and these findings is described in the PowerPoint presentation for Phase 1 of the project, and the knitted Word document containing R code, below:
### Phase 1 Files
[Phase 1 Summary](./Project_Ph1_VariableSelection.pptx)

[R Code](./BAN502_VariableSelect.docx)

## Phase 2 Key Findings

To follow the methods completed by the researcher, the order of the notebooks is:

1. Preprocessing --> /data_preprocessing/
1a. usepa_join_clean
--> Joining/initial trimming of usepa datasets from NRSA 2018-2019 dataset. Generally combined remotely-sensed vars with field data and physiographic divisions.

2. Exploratory Data Analysis --> /eda/
2a. usepa1819_eda
---> Includes selection of features process. Implements baseline model (power-law).

3. Feature Engineering --> /data_preprocessing/
3a. usepa_feature_engineering
--> Analyzes selected features from Step 2 and applies transformations. Alsos employs undersampling given target bias.

4. Model Building --> /training/
4a. USEPA_1819_Model_Building
--> Builds and evaluates four different ML models (Random Forest, FNN, Gradient Boosting, Extreme Gradient Boosting)

5. Evaluation --> /evaluation/
5a. USEPA_1819_Evaluation
--> Conducts accuracy, explainability analysis, etc. on selected model. Provides all figures found in /results/figures/
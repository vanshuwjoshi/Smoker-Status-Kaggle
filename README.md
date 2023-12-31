# Smoker Status Prediction using Bio-Signals

Welcome to the Smoking Prediction project! In this project, the goal is to predict a patient's smoking status based on various health indicators using binary classification.
The dataset includes information such as height, weight, fasting blood sugar level, cholesterol, triglyceride, and more.

![](https://images.theconversation.com/files/558645/original/file-20231109-17-q81n3u.jpg?ixlib=rb-1.1.0&rect=27%2C27%2C6078%2C4036&q=45&auto=format&w=496&fit=clip)

## Overview

### Problem Statement
Predict whether a patient is a smoker or a non-smoker based on health indicators. [Kaggle Link](https://www.kaggle.com/competitions/playground-series-s3e24/overview)

### Data Source
The dataset used for this project includes information about patients' health indicators. [Data](https://www.kaggle.com/competitions/playground-series-s3e24/data)

### Machine Learning Algorithms
Various machine learning algorithms were employed to predict smoking status, including logistic regression, decision trees, random forests, and XGBoost.

### Kaggle Score
The best result was achieved using the XGBoost algorithm, obtaining a Kaggle score of 0.77448.

## Key Findings

1. **Age and Smoking:**
   - People between the ages of 40-45 exhibit the highest rate of smokers.
    ![](https://www.kaggleusercontent.com/kf/152599256/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0.._eLj7cYoMw_6fDUBPXOUEQ.MG-jXRqp8EzoVgIX39AgxYOTra5JlaXV4uhPiCT8tiB1IEHSsxjfNnOIRsSlif7O1G_Nt9Yd68Tv_70nZZCrVMZjLFuOChq79_DaRso6byHI9TZu1ffyymXxkkRhgFDktCjUE8OZ4UUvLjdJ5IR9YtnOSRTYRhCtWg47idat0mpTOkRQ4Oc4URHgjv-A_dr7ib3MjCgCtrY-3uJh-QeYJWRGhoig_HD06eBYM9Fw7D1KvqaClwos1M-YEVx-__MeqHdLr4EGDAGov1e1WbTnFCPcjDjayxSE0FB2zxkdZ42qcqEj1jwzxClDr1p1Py1VIdj1f5iEqh__nCwgkxxPz1gRFozADZ52SSlgH7gvgEXSaCbhg0BqFy2ne0xjq1Zdk2UTIGmzv5q_aBvx7Mpf9Igurbh_Aw0NudAZbAc5EOi_5-r2k2YEGETfVMjD7oKkPR-6Xh7o3snoSjSda2jFqoJhbGuGWdvGscxPsIMNjB4x24k6LZPkZdq9TdJY8mPJm-iaynMDqts4Nd9Mgx75bet3TU2GnzTiD4t2vO80KNrR4iHkL5fsJ_-W5vgH0NfUagMR-mSns81jBb2JqZGKri8Zuwin7DOIa30WyTdhG06FNWo0zWMcUTFE6onXyEq_ZhZd1Dk14suw1TfMfbnpgg.DSqINYxGwLBQWNOmu6WO5g/__results___files/__results___16_1.png)

2. **Weight and Smoking:**
   - A higher weight is associated with a higher likelihood of smoking.
    ![](https://www.kaggleusercontent.com/kf/152599256/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0.._eLj7cYoMw_6fDUBPXOUEQ.MG-jXRqp8EzoVgIX39AgxYOTra5JlaXV4uhPiCT8tiB1IEHSsxjfNnOIRsSlif7O1G_Nt9Yd68Tv_70nZZCrVMZjLFuOChq79_DaRso6byHI9TZu1ffyymXxkkRhgFDktCjUE8OZ4UUvLjdJ5IR9YtnOSRTYRhCtWg47idat0mpTOkRQ4Oc4URHgjv-A_dr7ib3MjCgCtrY-3uJh-QeYJWRGhoig_HD06eBYM9Fw7D1KvqaClwos1M-YEVx-__MeqHdLr4EGDAGov1e1WbTnFCPcjDjayxSE0FB2zxkdZ42qcqEj1jwzxClDr1p1Py1VIdj1f5iEqh__nCwgkxxPz1gRFozADZ52SSlgH7gvgEXSaCbhg0BqFy2ne0xjq1Zdk2UTIGmzv5q_aBvx7Mpf9Igurbh_Aw0NudAZbAc5EOi_5-r2k2YEGETfVMjD7oKkPR-6Xh7o3snoSjSda2jFqoJhbGuGWdvGscxPsIMNjB4x24k6LZPkZdq9TdJY8mPJm-iaynMDqts4Nd9Mgx75bet3TU2GnzTiD4t2vO80KNrR4iHkL5fsJ_-W5vgH0NfUagMR-mSns81jBb2JqZGKri8Zuwin7DOIa30WyTdhG06FNWo0zWMcUTFE6onXyEq_ZhZd1Dk14suw1TfMfbnpgg.DSqINYxGwLBQWNOmu6WO5g/__results___files/__results___20_1.png)

3. **Fasting Blood Sugar and Smoking:**
   - There is a slightly increased chance of smoking with higher levels of fasting blood sugar.
     ![](https://www.kaggleusercontent.com/kf/152599256/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0.._eLj7cYoMw_6fDUBPXOUEQ.MG-jXRqp8EzoVgIX39AgxYOTra5JlaXV4uhPiCT8tiB1IEHSsxjfNnOIRsSlif7O1G_Nt9Yd68Tv_70nZZCrVMZjLFuOChq79_DaRso6byHI9TZu1ffyymXxkkRhgFDktCjUE8OZ4UUvLjdJ5IR9YtnOSRTYRhCtWg47idat0mpTOkRQ4Oc4URHgjv-A_dr7ib3MjCgCtrY-3uJh-QeYJWRGhoig_HD06eBYM9Fw7D1KvqaClwos1M-YEVx-__MeqHdLr4EGDAGov1e1WbTnFCPcjDjayxSE0FB2zxkdZ42qcqEj1jwzxClDr1p1Py1VIdj1f5iEqh__nCwgkxxPz1gRFozADZ52SSlgH7gvgEXSaCbhg0BqFy2ne0xjq1Zdk2UTIGmzv5q_aBvx7Mpf9Igurbh_Aw0NudAZbAc5EOi_5-r2k2YEGETfVMjD7oKkPR-6Xh7o3snoSjSda2jFqoJhbGuGWdvGscxPsIMNjB4x24k6LZPkZdq9TdJY8mPJm-iaynMDqts4Nd9Mgx75bet3TU2GnzTiD4t2vO80KNrR4iHkL5fsJ_-W5vgH0NfUagMR-mSns81jBb2JqZGKri8Zuwin7DOIa30WyTdhG06FNWo0zWMcUTFE6onXyEq_ZhZd1Dk14suw1TfMfbnpgg.DSqINYxGwLBQWNOmu6WO5g/__results___files/__results___35_1.png)

4. **Triglyceride and Smoking:**
   - A positive correlation exists between higher triglyceride levels and an increased likelihood of smoking.
   ![](https://www.kaggleusercontent.com/kf/152599256/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0.._eLj7cYoMw_6fDUBPXOUEQ.MG-jXRqp8EzoVgIX39AgxYOTra5JlaXV4uhPiCT8tiB1IEHSsxjfNnOIRsSlif7O1G_Nt9Yd68Tv_70nZZCrVMZjLFuOChq79_DaRso6byHI9TZu1ffyymXxkkRhgFDktCjUE8OZ4UUvLjdJ5IR9YtnOSRTYRhCtWg47idat0mpTOkRQ4Oc4URHgjv-A_dr7ib3MjCgCtrY-3uJh-QeYJWRGhoig_HD06eBYM9Fw7D1KvqaClwos1M-YEVx-__MeqHdLr4EGDAGov1e1WbTnFCPcjDjayxSE0FB2zxkdZ42qcqEj1jwzxClDr1p1Py1VIdj1f5iEqh__nCwgkxxPz1gRFozADZ52SSlgH7gvgEXSaCbhg0BqFy2ne0xjq1Zdk2UTIGmzv5q_aBvx7Mpf9Igurbh_Aw0NudAZbAc5EOi_5-r2k2YEGETfVMjD7oKkPR-6Xh7o3snoSjSda2jFqoJhbGuGWdvGscxPsIMNjB4x24k6LZPkZdq9TdJY8mPJm-iaynMDqts4Nd9Mgx75bet3TU2GnzTiD4t2vO80KNrR4iHkL5fsJ_-W5vgH0NfUagMR-mSns81jBb2JqZGKri8Zuwin7DOIa30WyTdhG06FNWo0zWMcUTFE6onXyEq_ZhZd1Dk14suw1TfMfbnpgg.DSqINYxGwLBQWNOmu6WO5g/__results___files/__results___39_1.png)

5. **Hemoglobin and Smoking:**
   - Higher hemoglobin levels are associated with a higher chance of smoking.
   ![](https://www.kaggleusercontent.com/kf/152599256/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0.._eLj7cYoMw_6fDUBPXOUEQ.MG-jXRqp8EzoVgIX39AgxYOTra5JlaXV4uhPiCT8tiB1IEHSsxjfNnOIRsSlif7O1G_Nt9Yd68Tv_70nZZCrVMZjLFuOChq79_DaRso6byHI9TZu1ffyymXxkkRhgFDktCjUE8OZ4UUvLjdJ5IR9YtnOSRTYRhCtWg47idat0mpTOkRQ4Oc4URHgjv-A_dr7ib3MjCgCtrY-3uJh-QeYJWRGhoig_HD06eBYM9Fw7D1KvqaClwos1M-YEVx-__MeqHdLr4EGDAGov1e1WbTnFCPcjDjayxSE0FB2zxkdZ42qcqEj1jwzxClDr1p1Py1VIdj1f5iEqh__nCwgkxxPz1gRFozADZ52SSlgH7gvgEXSaCbhg0BqFy2ne0xjq1Zdk2UTIGmzv5q_aBvx7Mpf9Igurbh_Aw0NudAZbAc5EOi_5-r2k2YEGETfVMjD7oKkPR-6Xh7o3snoSjSda2jFqoJhbGuGWdvGscxPsIMNjB4x24k6LZPkZdq9TdJY8mPJm-iaynMDqts4Nd9Mgx75bet3TU2GnzTiD4t2vO80KNrR4iHkL5fsJ_-W5vgH0NfUagMR-mSns81jBb2JqZGKri8Zuwin7DOIa30WyTdhG06FNWo0zWMcUTFE6onXyEq_ZhZd1Dk14suw1TfMfbnpgg.DSqINYxGwLBQWNOmu6WO5g/__results___files/__results___47_1.png)

## Project Structure

- **AnalysisNotebook.ipynb**: Jupyter Notebook containing the exploratory data analysis.
- **ModellingNotebook.ipynb**: Jupyter Notebook containing the preprocessing, and application of machine learning algorithms.

## Kaggle Competition Link

[Link to Kaggle Competition](https://www.kaggle.com/competitions/playground-series-s3e24/overview)

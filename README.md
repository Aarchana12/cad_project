# Machine Learning Model Deployment for Student Dropout

## Overview
This project focuses on deploying a machine learning model to predict student dropout rates in educational institutions. The aim is to assist institutions in making data-driven decisions to improve student retention. The model is deployed on IBM Cloud Watson Studio, and this README provides a comprehensive guide on how to use it.

## Table of Contents
1. [Project Objective](#project-objective)
2. [Approach](#approach)
3. [Project Progression](#project-progression)
4. [Dataset Overview](#dataset-overview)
5. [Chosen Model](#chosen-model)
6. [Integration and Deployment](#integration-and-deployment)
7. [Example API Request](#example-api-request)
8. [Possible Output](#possible-output)
9. [Innovative Technique](#innovative-technique)
10. [Conclusion](#conclusion)
11. [Documentation](#documentation)
12. [Submission](#submission)

## Project Objective
The primary goal of this project is to provide educational institutions with a tool to predict and mitigate student dropout rates. By leveraging machine learning and IBM Cloud Watson Studio, we aim to empower institutions to make informed decisions and improve student retention.

## Approach
The project is divided into several phases:
- **Phase 1:** Setting up IBM Cloud and Watson Machine Learning
- **Phase 2:** Deploying the model with Python
- **Phase 3:** Model deployment with metadata
- **Phase 4:** Deploying the model
- **Phase 5:** Scoring the deployed model

## Project Progression
The project progression includes the following phases:
- **Phase 3 - Project Development Part-1:** Dataset upload, cleansing, and exploratory data analysis.
- **Phase 4 - Project Development Part-2:** In-depth exploratory data analysis, modeling, and model selection.
- **Phase 5 - Finally Deploying the ML Model in IBM Cloud Watson Studio:** Deploying the model in IBM Cloud.

## Dataset Overview
The dataset used in this project provides valuable insights into student attributes, socioeconomic factors, and academic performance metrics. It covers a wide range of academic disciplines and allows for a thorough analysis of student attrition factors.

## Chosen Model
The Random Forest model has been selected for its high accuracy in predicting student dropout. It showcases an accuracy rate of 76.94%, making it the optimal choice for this task.

## Integration and Deployment
The project demonstrates how to integrate IBM Cloud and Watson Studio to deploy the machine learning model. It provides step-by-step instructions for deploying the model as a web service.

## Example API Request
Here's an example API request to make predictions using the deployed model:

```json
{
  "input_data": [
    {
      "MaritalStatus": "Single",
      "ApplicationMode": "Online",
      "ApplicationOrder": 3,
      "Course": "Engineering",
      "DaytimeOrEveningAttendance": "Daytime",
      "PreviousQualification": "High School Diploma",
      "Nationality": "US",
      "MothersQualification": "Bachelor's Degree",
      "FathersQualification": "Master's Degree",
      "MothersOccupation": "Engineer",
      "FathersOccupation": "Doctor",
      "Displaced": "No",
      "EducationalSpecialNeeds": "No",
      "Debtor": "No",
      "TuitionFeesUpToDate": "Yes",
      "Gender": "Male",
      "ScholarshipHolder": "Yes",
      "AgeAtEnrollment": 19,
      "InternationalStudent": "No",
      "CurricularUnits1stSemCredited": 5,
      "CurricularUnits1stSemEnrolled": 6,
      "CurricularUnits1stSemEvaluations": 6,
      "CurricularUnits1stSemApproved": 6
    }
  ]
}



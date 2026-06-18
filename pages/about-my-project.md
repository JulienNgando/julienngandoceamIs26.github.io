---
layout: project
title: About My Project
permalink: /about-my-project.html
subtitle: Human-Computer Interaction & Adaptive Systems
project_title: "AI-Driven PM2.5 Prediction Using Satellite and Meteorological Data"

problem: |
  Aerosols are tiny particles suspended in the air. Among them is PM2.5, which refers to particles smaller than 2.5 micrometers in diameter—small enough to be inhaled deeply and even lodged between cells, causing major health implications like lung inflammation and cancer. Traditionally, these hazardous air pollutants are measured using standard monitoring stations. While highly accurate, these stations are bulky, expensive, and difficult to maintain, which leaves them sparsely distributed and creates large gaps in our air quality data.

  Fortunately, recent technological advances have introduced Next Generation Air Monitoring (NGAM) devices. These smaller, affordable units use compact sensors to measure air pollution, temperature, and pressure across wider areas, wirelessly sending the data to remote servers for analysis. Using the data collected from these modern devices, my research group aims to use Machine Learning to predict PM2.5 concentrations in the air and determine which models are the most accurate at accomplishing this task.

approach: |
  * **Step 1 — Data Collection and Cleaning:** We will first collect and aggregate raw PM2.5 concentration levels and atmospheric data from the Howard, Pandonia, and Beltsville monitoring sites. In this initial phase, we will align the datasets and handle missing or corrupted data points to ensure a consistent baseline for analysis.
  * **Step 2 — Data Interfacing and Preprocessing:** Next, we will break the data into precise 30-minute and hourly intervals to capture fine-grained temporal trends. During this step, we will also perform feature engineering and filter out anomalies, such as removing physically impossible negative values, to ensure high data quality.
  * **Step 3 — Model Training and Feature Selection:** We will then split the preprocessed data into training and testing sets to evaluate model generalization. We will implement feature selection methods (like Mutual Information) to determine the most impactful predictors, allowing our machine learning models—specifically XGBoost, LightGBM, and CatBoost, alongside baseline regressions—to learn and predict PM2.5 concentration trends accurately.
  * **Step 4 — Evaluation and Communication of Results:** Finally, we will evaluate the models using standard metrics like Root Mean Squared Error (RMSE) and R2 scores to determine which algorithms are the most accurate. We will communicate these findings by neatly organizing the codebase into reusable workflows for the research team and presenting weekly progress and performance visualizations to our research group and advisors.

outcome: |
  By the end of the program, I expect to produce a cohesive suite of research and software artifacts, including a clean and well-documented Python code repository, a structured short research paper, and a comprehensive research poster. The code repository will feature our optimized data pipeline—complete with data cleaning, interval resampling, and trained XGBoost, LightGBM, and CatBoost models—allowing my research teammates and future students to seamlessly plug in their own localized atmospheric datasets without reinventing the workflow. Meanwhile, the short paper and research poster will visually and textually communicate our methodology, feature engineering insights, and model performance metrics (R2 and RMSE). Ultimately, I hope these artifacts will allow environmental scientists and public health officials to easily see which machine learning architectures are most reliable for high-resolution PM2.5 tracking, helping them better understand and address micro-scale air pollution trends in localized communities.

final_report_url: https://example.com/your-report.pdf

grad_mentor:
  name: Rokeya Siddiqua
  linkedin: https://www.linkedin.com/in/example

faculty_mentor:
  name: Dr. Xiaowen Li
  linkedin: https://www.linkedin.com/in/example
---

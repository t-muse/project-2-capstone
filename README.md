## Author

Thealisha Muse  
AI08-PT-CAP-01

# Modeling the Impact of Multitasking and Distraction on Productivity

## Overview

This project analyzes how multitasking, interruptions, and workload structure impact employee productivity. Using machine learning, the analysis identifies key drivers of performance and provides actionable recommendations for improving how work is designed in modern, digitally connected environments.

The goal is to move beyond activity-based metrics and develop a clearer understanding of how work patterns influence meaningful output.

## Business Problem

Organizations often measure productivity using surface-level indicators such as hours worked or number of meetings. However, these metrics do not capture how work is experienced or how interruptions and multitasking affect performance.

This project addresses the lack of visibility into how workload, meeting frequency, and cognitive strain influence productivity outcomes, particularly in remote and hybrid work environments.

## Objectives

- Identify the key drivers of productivity using machine learning
- Understand how meetings, workload, and stress interact to influence outcomes
- Detect patterns of diminishing returns in high-activity work environments
- Translate model results into actionable recommendations for work design

## Datasets

This project uses two complementary datasets:

- **Remote Worker Productivity Dataset (Hugging Face)**  
  ~1,500 records capturing productivity outcomes, work structure, and wellbeing indicators

- **Focus and Distraction Dataset (Human Clarity Institute)**  
  ~790 records capturing behavioral patterns related to interruptions, multitasking, and cognitive load

The datasets are used together to connect how work is performed with resulting productivity outcomes.

## Approach

The project follows a structured machine learning workflow:

- Exploratory Data Analysis (EDA) to identify patterns and relationships
- Data preparation and feature engineering using a scikit-learn Pipeline
- Model development using:
  - Linear Regression (baseline)
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Model evaluation using cross-validation and test set performance
- Feature importance analysis to identify key productivity drivers

## Key Findings

- Productivity is influenced by a combination of workload, meeting frequency, and stress
- Increased activity does not consistently lead to increased productivity
- Evidence of diminishing returns was observed in high-meeting and high-workload scenarios
- Interruptions and task switching reduce the ability to sustain focused work
- Behavioral data shows that employees often feel busy without accomplishing meaningful output

## Recommendations

- Reduce unnecessary meetings and consolidate collaboration
- Protect uninterrupted focus time to support deep work
- Manage workload based on capacity rather than hours worked
- Incorporate stress and wellbeing into performance management
- Shift from activity-based metrics to outcome-based performance measures

## Project Structure

project-2-capstone/
│
├── Data/                  # Source datasets
├── models/                # Serialized model pipeline
├── project-deliverables/  # Project Pitch and Jupyter notebooks
├── README.md              # Project overview

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## How to Run

1. Clone the repository
2. Navigate to the project folder
3. Install dependencies
4. Open and run the notebook

Example:

git clone https://github.com/YOUR-USERNAME/project-2-worker-productivity-ml.git
cd project-2-worker-productivity-ml
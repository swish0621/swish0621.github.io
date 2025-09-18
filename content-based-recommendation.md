---
title: Content-Based Recommendation System
---

# Project: Content Based Recommendation System

## Vision Statement
This project aims to provide experience with popular technology stacks while also producing a portfolio worthy project. It will deepen my understanding of recommendation systems and practical machine learning workflows.

## Motivation
Recommendation systems are used all over the place in industry, from streaming apps to online shopping. I picked this project to get hands-on experience building one, improve my technical skills, and better understand how these systems work in real world applications.

## Goals

### 1. Dataset Selection
- Obtain a dataset with at least 1,000 items and 5 or more attributes (currently planning to use a movie dataset).  
- Clean and preprocess the dataset.  
- Convert the attributes into a format suitable for vector-based similarity calculations.  

### 2. Features
- Implement at least two similarity measures (ex. Euclidean distance and Cosine similarity).  
- Compare the effectiveness of each method.  
- Verify that the functionality works correctly.  

### 3. Recommendation System
- Return the top 5 most similar items for a single item or a user’s history.  
- Ensure the system has reasonable runtime for any input.  

### 4. FastAPI and SQLite Implementation
- Deploy the recommendation system as a FastAPI service.  
- Connect FastAPI to a SQLite database for data retrieval and storage.  

### 5. Testing
- Select at least one metric to measure recommendation precision (ex. Precision@5).  
- Ensure the system is consistent across different inputs.  
- Report the precision and other relevant evaluation results.

## Tools & Technologies
- **Python** — primary programming language.
- **FastAPI** — lightweight web framework.
- **SQLite** — relational database for storing item data and user interactions.
- **Jinja2 Templates** — for minimal frontend UI served via FastAPI.
- **Pandas / NumPy / Scikit-learn** — for data preprocessing, vectorization, and similarity calculations.

## Risks to Completion & Mitigation
**Unfamiliarity with FastAPI and SQLite**
  - Mitigation: Spend time upfront learning the frameworks and doing practice exercises.  

**Balancing workload with other classes and career commitments**
  - Mitigation: Use a weekly schedule with clear objectives to stay on track.  

**Scope Creep**
  - Mitigation: Clearly define the MVP and only add extra features if time allows.  

**Dataset Availability and Quality**
  - Mitigation: Use publicly available datasets (ex. Kaggle) and clean the data early in the project.  

## Assessments
The finished project should:  
- Provide a functional FastAPI backend capable of producing recommendations through at least one endpoint.  
- Use a SQLite database to store item data and any user interactions.  
- Successfully generate accurate recommendations based on a single input or user history.  
- Include clear documentation to install, run, and test the system.  

## Repository Link
[Content Based Recommendation System GitHub Repository](https://github.com/swish0621/Content-Based-Recommendation-System-.git)



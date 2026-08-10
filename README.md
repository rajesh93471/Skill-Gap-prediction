# Curriculum–Industry Skill Alignment Decision Framework

## Overview

This project identifies employability skill gaps among Computer Science Engineering (CSE) students using Machine Learning and the Feast feature store.

A student skill dataset containing 100 records is used to analyze academic and technical skills. A Decision Tree Classifier is used to predict whether a student is **Industry Ready** or has a **Skill Gap**.

The project also demonstrates how **Feast** can be used to manage student features, retrieve historical features for model training, and retrieve online features for real-time prediction.

---

## Objectives

- Identify employability skill gaps among CSE students.
- Analyze academic and technical student attributes.
- Store and manage ML features using Feast.
- Retrieve historical features for model training.
- Train a Decision Tree classification model.
- Predict whether students are Industry Ready or have a Skill Gap.
- Perform online feature retrieval and prediction using Feast.

---

## Features

The dataset contains 100 student records with the following attributes:

- CGPA
- Python
- Java
- Data Structures and Algorithms (DSA)
- Database Management Systems (DBMS)
- Operating Systems (OS)
- Computer Networks (CN)
- Web Development
- Communication Skills
- Aptitude
- Projects
- Internship
- Certifications
- Industry Readiness

---

## Dataset

The project uses a synthetic dataset containing **100 CSE student records**.

### Target Variable

`Industry_Readiness`

The target contains two categories:

- **Ready** – Student is predicted to be Industry Ready.
- **Gap** – Student requires additional skill development.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Google Colab
- Feast
- PyArrow
- SQLite

---

# Machine Learning

## Model

### Decision Tree Classifier

A Decision Tree Classifier is used to classify students based on their academic and technical skill profiles.

The model uses features such as:

- CGPA
- Python
- Java
- DSA
- DBMS
- OS
- CN
- Web Development
- Communication
- Aptitude
- Projects
- Internship
- Certifications

The model predicts:

```text
Industry Ready
       OR
Skill Gap
Konda Rajesh

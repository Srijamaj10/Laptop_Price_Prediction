# Laptop Price Prediction

## Table of Contents

1. [Introduction](#introduction)  
2. [Project Objective](#project-objective)  
3. [Features](#features)  
4. [Dataset](#dataset)  
5. [Modeling and Algorithm](#modeling-and-algorithm)  
6. [Website Integration](#website-integration)  
7. [Performance Evaluation](#performance-evaluation)  
8. [Prerequisites](#prerequisites)  
9. [Contact](#contact)  

---

### Introduction

The Laptop Price Prediction project is a machine learning solution that predicts laptop prices based on a range of configurations. The model is designed to assist users—especially students and budget-conscious buyers—in making informed decisions when comparing laptop prices with desired specifications.

---

### Project Objective

This project addresses a real-world problem by helping users quickly and accurately estimate laptop prices across different brands and configurations. Users can compare prices and features conveniently on a single platform.

---

### Features

The model predicts prices based on the following key features:

- **Brand:** Type of laptop manufacturer.
- **RAM:** Amount of RAM.
- **Weight:** Weight of the laptop.
- **Touchscreen:** Availability of touchscreen.
- **IPS Display:** Presence of an IPS screen.
- **Screen Size:** Physical size of the display.
- **Resolution:** Screen resolution.
- **CPU:** Type of processor.
- **HDD:** Hard disk drive capacity.
- **SSD:** Solid-state drive capacity.
- **GPU:** Graphics processing unit.
- **Operating System:** Installed operating system.

---

### Dataset

The dataset used includes a wide range of laptops and their respective configurations. Prices in the dataset reflect current market values, which enable accurate model training and validation.

- **Source:** [Laptop Dataset](https://github.com/campusx-official/laptop-price-predictor-regression-project/blob/main/laptop_data.csv)  
- **Size:** (1303, 12)

---

### Modeling and Algorithm

This project uses the **Random Forest Regression** algorithm, selected for its robustness and capability to handle various features effectively.

- **Algorithm:** Random Forest Regression  
- **Model Score:**  
    - R2 Score: 0.8873402378382488  
    - MAE: 0.15860130110457718  
- **Accuracy:** The model achieves minimal error, with approximate differences of only a few thousand compared to actual prices (e.g., if predicted price is INR 74,000, actual might be INR 78,000).

---

### Website Integration

A user-friendly web interface has been created for this model:

- **Features:** Allows users to input laptop specifications and receive an approximate price.
- **Functionality:** Displays real-time predictions that users can compare with prices on major platforms such as Amazon and Flipkart.
- **Platform:** Built using Streamlit.

---

### Performance Evaluation

The model’s performance is validated against actual prices:

- **Prediction Comparison:** Example predictions show minimal error, consistently staying within a small margin of actual market prices.

---

### Prerequisites

- **Python version:** >= 3.9.12
- **Libraries:**  
    - scikit-learn  
    - pandas  
    - numpy  
    - streamlit  
    - seaborn  

---

### Contact

For any queries or further information, feel free to reach out!
Srija Majumdar Linkdin - https://www.linkedin.com/in/srija-majumdar-a686772a2


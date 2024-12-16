# Sepsis Survival Prediction using Machine Learning

This project predicts patient survival outcomes for sepsis-related hospital admissions using machine learning techniques. It is structured as a binary classification problem with extreme class imbalance.

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Project Structure](#project-structure)
5. [Usage](#usage)
6. [Results](#results)
7. [License](#license)

---

## Overview
Sepsis is a critical medical condition with high mortality rates. The goal of this project is to predict whether hospitalized patients with sepsis are likely to survive or not, based on key features such as age, sex, and episode number.  

We applied several machine learning models, evaluated using the AUC-PR metric, and focused on addressing the minority class (deceased patients).

---

## Dataset
The dataset comprises **110,204 hospital admissions** from Norway (2011–2012). It includes:
- **Age** (numeric)
- **Sex** (male/female)
- **Episode Number** (categorical)  

Since the dataset is large, download it from:  
[Dataset Link](<https://archive.ics.uci.edu/dataset/827/sepsis+survival+minimal+clinical+records>)

---

## Installation
To set up this project, ensure you have **Python 3.8+**. Install the required packages using the provided YAML file:

```bash
conda env create -f environment.yaml
conda activate data1030

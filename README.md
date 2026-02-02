# Titanic — Exploratory Analysis and Supervised Survival Modelling

This project explores the classic Titanic dataset through a structured analytical progression, beginning with **exploratory data analysis (EDA)** and extending into **supervised machine learning models** for survival prediction.

Given how frequently this dataset is used, the project was approached with the intention of demonstrating **careful data handling, disciplined reasoning, and clear interpretation**, rather than reproducing commonly reported outcomes. The analysis progresses from exploratory understanding to interpretable modelling and finally to an ensemble-based approach to improve predictive performance.

![Black and white illustration of the sinking of the Titanic. The Titanic ocean liner is going down by the head with the stern in the air, showing the propellers. There are icebergs in the background. In the foreground, survivors are rowing wooden lifeboats.](Stöwer_Titanic.jpg?raw=true)

---

## What’s in this repository

- **Jupyter Notebooks:**  
  - Exploratory data analysis (`titanic.ipynb`)  
  - Decision tree model (`decision_tree_titanic.ipynb`)  
  - Random forest model (`random_forest_titanic.ipynb`)  
- **Dataset:** Titanic passenger data  
- **Images:** visualisations, tree diagrams, and reviewer feedback  
- **Requirements:** Python dependencies (`requirements.txt`)  

---

## Project Context

The Titanic dataset contains passenger demographic, socioeconomic, and travel information alongside a binary survival outcome. While often treated as a demonstration dataset, it provides a useful benchmark for examining analytical judgement, feature interpretation, and modelling assumptions.

The objective of this project was to:

- Understand which factors influenced survival outcomes  
- Explore how survival patterns relate to class, age, sex, and fare  
- Develop predictive models while balancing interpretability and performance  

---

## Approach Overview

The analysis followed a deliberate progression:

- Exploratory data analysis and careful handling of missing values  
- Visual and statistical examination of relationships between features and survival  
- Development of an interpretable decision tree model  
- Evaluation of model complexity and overfitting behaviour  
- Extension to a random forest classifier to improve generalisation performance  

Each stage built on insights from the previous one, reinforcing understanding before increasing model complexity.

---

## Key Insights / Findings

- Survival was strongly associated with **passenger class, age, fare, and sex**.  
- Careful treatment of missing age values was essential to avoid introducing bias.  
- Decision trees provided interpretability but were sensitive to depth and overfitting.  
- Random forest modelling improved predictive accuracy and stability through ensemble learning.  
- Feature importance analysis highlighted a small subset of predictors that dominated model behaviour.  

Overall, the project demonstrates the trade-offs between interpretability and performance in supervised learning.

---

## Endorsement

Reviewer feedback highlighted the **depth and thoroughness of the exploratory analysis**, with particular praise for:

- The **careful and well-reasoned handling of missing age values**  
- The **comprehensive nature of the exploratory work**  
- A clear, methodical approach that went beyond surface-level analysis  

The feedback emphasised the strength of the analytical foundation established prior to modelling.

<sub>[View full reviewer feedback](Titanic%20feedback.jpg)</sub>

---

## Skills Demonstrated

**Analysis**
- Exploratory data analysis  
- Thoughtful handling of missing data  
- Interpretation of feature relationships  

**Modelling**
- Decision tree classification  
- Random forest classification  
- Ensemble learning concepts  

**Evaluation**
- Overfitting analysis and pruning strategies  
- Feature importance interpretation  
- Model comparison  

**Tools**
- Python  
- pandas  
- scikit-learn  
- matplotlib / seaborn  
- Jupyter Notebook  

---

## Requirements

Install the required Python dependencies with: `pip install -r requirements.txt` . *Note: Visualisation of decision trees requires Graphviz to be installed on the system.*

---

## Why this project belongs in my portfolio

The Titanic dataset is widely used, making it a strong benchmark for analytical judgement.

This project demonstrates a complete analytical progression: from exploratory understanding, through interpretable modelling, to an ensemble approach that improves predictive performance. It reflects a balanced approach to machine learning that prioritises data understanding, methodological discipline, and realistic evaluation over novelty or optimisation alone.

This project demonstrates a full analytical progression: beginning with exploratory understanding, moving through interpretable modelling, and culminating in an ensemble approach to improve predictive performance. Together, these stages reflect both analytical reasoning and applied machine learning fundamentals.

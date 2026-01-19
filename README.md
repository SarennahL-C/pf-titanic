# Titanic — Exploratory Data Analysis of Survival Patterns and Decision Tree Survival Model

This project explores the classic Titanic dataset through a two-stage analysis: an initial **Exploratory Data Analysis (EDA)** followed by a **supervised machine learning model** to predict passenger survival.

Given how frequently this dataset is used, I approached the project with the intention of demonstrating **careful data handling, thoughtful reasoning, and clear interpretation**, rather than simply reproducing commonly reported results.

I found myself particularly engaged in the data cleaning stage — especially addressing missing values — and used this project to strengthen my analytical workflow and attention to detail. Building on the insights from the EDA, I then developed a decision tree model to explore survivability from a predictive perspective.

![Black and white illustration of the sinking of the Titanic. The Titanic ocean liner is going down by the head with the stern in the air, showing the propellers. There are icebergs in the background. In the foreground, survivors are rowing wooden lifeboats.](Stöwer_Titanic.jpg?raw=true)

### What's in this repository
- **Jupyter Notebooks**
  - Exploratory data analysis: `titanic.ipynb`
  - Decision tree model: `decision_tree_titanic.ipynb`
- **Images:** visualisations, tree diagrams, and reviewer feedback
- **Dataset:** Titanic passenger data
- **Requirements:** Python dependencies (`requirements.txt`)

## Part 1: Exploratory Data Analysis (EDA)  
`titanic.ipynb`

### Context

The first stage of the project focuses on understanding survival outcomes on the RMS Titanic through exploratory analysis. The guiding questions included:

- What factors most strongly influenced survival?
- Did passenger class affect access to lifeboats?
- Does the data support the “women and children first” principle?
- What additional patterns emerge from the dataset?

Rather than rushing to conclusions, I focused on building a clear analytical foundation before interpreting results.

### Approach and Key Insights

The EDA combines structured data cleaning with exploratory visualisation:

- **Missing data treatment:** Particular care was taken in handling missing age values, with assumptions made explicit and justified.
- **Correlation analysis:** Heatmaps were used to identify relationships between numerical variables and survival.
- **Passenger class effects:** Grouped bar charts highlighted survival advantages associated with higher passenger classes.
- **Gender and age patterns:** Stacked histograms explored differences across sex and age groups.
- **Embarkation insight:** A positive survival association with embarkation at Cherbourg was identified and traced back to class distribution rather than location alone.

Throughout the analysis, I aimed to distinguish correlation from causation and to explain *why* patterns appeared, not just *that* they did.

### Endorsement

Reviewer [feedback](./Titanic%20feedback.jpg) highlighted the **depth and thoroughness of the analysis**, with particular praise for:

- The **careful and well-reasoned handling of missing age values**
- The **comprehensive nature of the exploratory work**
- A clear, methodical approach that went beyond surface-level analysis

### Skills Demonstrated (EDA)

- Data cleaning and preprocessing  
- Thoughtful handling of missing data  
- Exploratory visualisation (heatmaps, histograms, grouped charts)  
- Analytical reasoning and interpretation  
- Python, pandas, seaborn, matplotlib, Jupyter Notebook

## Part 2: Decision Tree Model (Supervised Machine Learning 
`decision_tree_titanic.ipynb`

### Model Context

Building on the insights gained during the exploratory phase, the second part of the project introduces a **decision tree classifier** to model passenger survival.

The aim was not only to generate predictions, but to understand how model complexity influences performance and how overfitting emerges in practice.

### Approach and Key Insights

Given the relatively small size of the dataset, I explored multiple decision tree configurations:

- Models were trained with varying maximum depths
- Accuracy was evaluated on both training and development datasets
- Performance was analysed as a function of pruning depth

![Accuracy vs pruning depth](accuracy_vs_pruning_depth.png)

The training accuracy increased monotonically with depth, indicating progressively better fit to the training data.

In contrast, development accuracy showed variability, with local maxima at **max_depth = 6 and 9**, and a noticeable decline at **max_depth = 10**. This divergence illustrates how deeper trees begin modelling noise rather than generalisable patterns.

The intersection of training and development performance indicated that **max_depth = 6** represented the most appropriate balance between bias and variance. Where similar accuracies occurred, the simpler model was preferred to reduce the risk of overfitting.

This analysis provided a practical demonstration of model complexity, generalisation, and the limitations of decision trees on small datasets.

### Skills Demonstrated (Modelling)

- Supervised machine learning with decision trees  
- Model evaluation using training and development splits  
- Overfitting analysis and pruning strategy  
- Interpretation of model performance trends  

### Requirements

Install the required Python dependencies with: `pip install -r requirements.txt`

### Why this project belongs in my portfolio

The Titanic dataset is widely used, making it a strong benchmark for analytical judgement.

This project reflects how I approach familiar problems: first by developing a deep understanding of the data, and then by applying supervised learning techniques thoughtfully rather than mechanically. Together, the EDA and modelling stages demonstrate both analytical reasoning and applied machine learning fundamentals.

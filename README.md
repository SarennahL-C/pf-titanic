# Titanic — Exploratory Data Analysis of Survival Patterns

This project presents a detailed **Exploratory Data Analysis (EDA)** of the classic Titanic [dataset](https://github.com/SarennahL-C/pf-titanic/blob/69a642be9527a974a3509388138ab50eee0b7283/Titanic.csv), completed as part of a data science bootcamp. Given how frequently this dataset is used, I approached it with the intention of demonstrating **careful data handling, thoughtful analysis, and clear reasoning**, rather than simply reproducing expected outcomes.

I found myself particularly engaged in the data cleaning stage — especially addressing missing values — and used this project to strengthen my analytical workflow and attention to detail.

![Black and white illustration of the sinking of the Titanic. The Titanic ocean liner is going down by the head with the stern in the air, showing the propellers. There are icebergs in the background. In the foreground, survivors are rowing wooden lifeboats.](Stöwer_Titanic.jpg?raw=true)

### What's in this repository
- **Jupyter Notebook:** step-by-step analysis and findings (`titanic.ipynb`)  
- **Images:** visuals and reviewer feedback  
- **Requirements:** Python dependencies (`requirements.txt`)

### Project Context

The task was to create a Jupyter Notebook exploring survival outcomes on the RMS Titanic and to investigate several guiding questions, including:

- What factors most strongly influenced survival?
- Did passenger class affect access to lifeboats?
- Does the data support the “women and children first” principle?
- What additional patterns emerge from the data?

Rather than rushing to conclusions, I focused on building a solid analytical foundation before interpreting results.

### Approach and Key Insights

The analysis combines structured data cleaning with exploratory visualisation:

- **Missing data treatment:** Particular care was taken in handling missing age values, ensuring assumptions were explicit and justified.
- **Correlation analysis:** A correlation matrix and heatmap were used to identify relationships between numerical variables and survival.
- **Passenger class effects:** Grouped bar charts highlighted clear survival advantages associated with higher passenger classes.
- **Gender and age patterns:** Stacked histograms were used to explore survival differences across sex and age groups.
- **Embarkation insight:** A positive survival association with embarkation at Cherbourg was identified and traced back to class distribution rather than location alone.

Throughout the analysis, I aimed to distinguish correlation from causation and to explain *why* patterns appeared, not just *that* they did.

### Endorsement

Reviewer [feedback](./Titanic%20feedback.jpg) highlighted the **depth and thoroughness of the analysis**, with particular praise for:

- The **careful and well-reasoned handling of missing age values**
- The **comprehensive nature of the exploratory work**
- A clear, methodical approach that went beyond surface-level analysis

### Skills Demonstrated

- Data cleaning and preprocessing  
- Thoughtful handling of missing data  
- Exploratory visualisation (heatmaps, histograms, grouped charts)  
- Analytical reasoning and interpretation  
- Python, pandas, seaborn, matplotlib, Jupyter Notebook  

### Requirements

Install the required Python dependencies with: `pip install -r requirements.txt`

### Why this project belongs in my portfolio

The Titanic dataset is widely used, which makes it a useful benchmark for analytical judgement. This project reflects how I approach well-known problems: by slowing down, questioning assumptions, and prioritising clarity and rigour over novelty.

### Portfolio
I'm curating a portfolio of data science projects I've worked on or am currently working on. Some are for fun and curiosity; others came from a data science bootcamp.

# Titanic
Like many others, my first significant data science project is based on a version of the Titanic dataset. I admit to getting engrossed in the cleaning process and arriving at the analysis feeling excited to build on that foundation and demonstrate the historically expected results.

The project was a bootcamp task to:

> Create a Jupyter notebook called titanic.ipynb. Use this notebook to create an in-depth EDA on the Titanic [dataset](https://github.com/SarennahL-C/pf-titanic/blob/69a642be9527a974a3509388138ab50eee0b7283/Titanic.csv) provided. Your EDA should contain descriptions of each step and appropriate visualisations. Use the metadata for the Titanic dataset to familiarise yourself with the data.
Use the following guiding questions for your EDA:
> 1. What is the most important factor in determining whether a person was likely to survive the sinking of the Titanic?
> 2. In the movie, the upper-class passengers were given preference on lifeboats. Does this show in the data?
> 3. “Women and children first”. Was this the case?
> 4. Add one other observation that you have noted in the dataset.

1. To find the most important factor for survival, I found the correlation matrix and showed the correlation heatmap.
2. To determine if upper-class passengers were prioritised for the lifeboats, I used pandas.groupby() and a grouped bar chart.
3. I used stacked histograms to check whether the famous phrase "women and children first" was enacted.
4. My observation concerned a weak positive correlation between survival and embarking in Cherbourg. On investigation, the correlation occurs because of the high proportion of 1st class passengers joining the Titanic in Cherbourg.

The reviewer's feedback on my project especially highlighted my detailed treatment of the missing age values and the comprehensive nature of my work. View a screenshot of the feedback [here](https://github.com/SarennahL-C/pf-titanic/blob/43051997789de3818f7b4399fa02fa4345319dc0/Titanic%20feedback.jpg).

#### Requirements
Install the requirements for Python 3 using `pip install -r requirements.txt`.

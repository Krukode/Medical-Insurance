# U.S. Medical Insurance Costs Analysis

## Overview
This project investigates a medical insurance costs dataset using Python. The goal is to analyze the data to uncover insights about patient demographics and insurance charges. The analysis focuses on identifying trends, answering specific questions, and visualizing key findings through charts and graphs. The project is part of a data analytics portfolio, showcasing Python skills, data manipulation, and visualization expertise.

## Dataset
The dataset, `insurance.csv`, contains the following fields:
- **age**: Age of the primary beneficiary.
- **sex**: Gender of the individual (male or female).
- **bmi**: Body Mass Index (BMI) of the individual.
- **children**: Number of children/dependents covered by the insurance.
- **smoker**: Smoking status of the individual (yes or no).
- **region**: Geographic region of the individual (northeast, northwest, southeast, southwest).
- **charges**: Individual medical insurance costs billed.

## Key Questions Addressed
- What is the average age of the patients in the dataset?
- Where are a majority of the individuals from?
- How do the insurance charges compare between smokers and non-smokers?
- What is the average age of individuals with at least one child?

## Tools and Libraries Used
- **Python** for data analysis.
- **Pandas** for data manipulation and exploration.
- **Matplotlib** and **Seaborn** for data visualization.

## Methodology

### Data Inspection:
- Checked for missing or duplicate values.
- Analyzed the structure and overview of the dataset.

### Data Preparation:
- Encoded categorical variables (`sex`, `smoker`, `region`) into numerical values using one-hot encoding.
- Generated summary statistics to explore numerical features.

### Analysis and Visualization:
- Explored distributions and patterns in the data.
- Created visualizations to answer the key questions.
- Conducted additional analysis to uncover insights such as correlations between variables.

## Key Findings
- The average age of the patients is approximately 39 years.
- A majority of the individuals are from the Southeast region.
- Smokers incur significantly higher insurance charges compared to non-smokers, as shown in both descriptive statistics and visualizations.
- The average age of individuals with at least one child is also around 39 years, similar to the overall average.

## Visualizations
1. **Patient Distribution by Region**: A countplot reveals that most patients are located in the Southeast.
2. **Insurance Charges by Smoking Status**: Boxplots and descriptive statistics indicate that smokers face higher insurance charges than non-smokers.
3. **Correlation Heatmap**: A heatmap illustrates the relationships between numerical variables, highlighting a strong positive correlation between smoking and insurance charges.
4. **Scatterplot: Smoking Status vs. Charges**: A scatterplot shows the stark difference in charges between smokers and non-smokers.

## How to Run the Project
1. Clone this repository to your local machine.
2. Install the required libraries (listed in `requirements.txt`).
3. Run the Jupyter Notebook or Python script to execute the analysis.

## Conclusion
This project provides valuable insights into the factors influencing medical insurance costs. By exploring relationships between variables such as smoking status, region, and charges, the analysis highlights the significant impact of lifestyle and demographics on insurance expenses.
The project demonstrates data analysis and visualization techniques in Python, making it an ideal addition to a data analytics portfolio.

## Contact
For questions or feedback, feel free to connect via [GitHub Profile](https://github.com/your-profile).

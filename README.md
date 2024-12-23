# Student Admissions Analysis

## Overview
Analysis of student admissions trends in India (2019-2024) and their correlation with economic and social factors; data is not owned by me, credit goes to the respective sources.
The **Student Admissions Analysis** project aims to explore the trends in student admissions in India from **2019 to 2024**. This analysis investigates the correlation between student admissions and various economic and social factors, including GDP growth, advancements in artificial intelligence (AI), the impact of COVID-19, and average salaries. The goal of this project is to provide insights into the factors influencing educational enrollment and help policymakers and educational institutions make informed decisions.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Analysis](#analysis)
- [Visualizations](#visualizations)
- [Results](#results)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)
- [Contact Information](#contact-information)

## Installation
To run this project, you need to have Python installed on your machine. You can install the required libraries using pip. Follow these steps: 1. **Install Python**: Make sure you have Python 3.x installed. You can download it from [python.org](https://www.python.org/downloads/). 2. **Install Required Libraries**: Open your terminal or command prompt and run the following command: ```bash pip install pandas matplotlib seaborn ``` This command will install the necessary libraries for data manipulation and visualization.

## Usage
1. **Clone the Repository**: Start by cloning the repository to your local machine. Use the following command: ```bash git clone https://github.com/yourusername/student-admissions-analysis.git ``` Replace `yourusername` with your actual GitHub username. 2. **Navigate to the Project Directory**: ```bash cd student-admissions-analysis ``` 3. **Run the Analysis Script**: Execute the analysis script to perform the data analysis and generate visualizations: ```bash python analysis.py ``` This will run the analysis and display the results in the console, along with generating visualizations.

## Data

The project uses the following datasets:

- **Student Admissions Data**: Contains the number of students admitted from 2019 to 2024.
  
  | Year | Admissions |
  |------|------------|
  | 2019 | 15         |
  | 2020 | 8          |
  | 2021 | 8          |
  | 2022 | 5          |
  | 2023 | 12         |
  | 2024 | 26         |

- **Salary Data**: Includes average salaries in INR from 2019 to 2024.
  
  | Year | Salary (INR) |
  |------|--------------|
  | 2019 | 600,000      |
  | 2020 | 700,000      |
  | 2021 | 800,000      |
  | 2022 | 900,000      |
  | 2023 | 1,000,000    |
  | 2024 | 1,200,000    |

- **GDP Growth Data**: Provides GDP growth percentages for the same years.
  
  | Year | GDP Growth (%) |
  |------|----------------|
  | 2019 | 4.0            |
  | 2020 | -6.6           |
  | 2021 | 8.9            |
  | 2022 | 7.2            |
  | 2023 | 6.3            |
  | 2024 | 7.0            |

- **AI Developments Data**: Information on advancements in AI technologies and their impact on education.

- **COVID-19 Data**: Tracks new COVID-19 cases reported during the analysis period.

## Analysis
The analysis includes several key components: 1. **Data Cleaning**: The datasets are cleaned and preprocessed to ensure consistency and accuracy. This includes handling missing values and ensuring data types are correct. 2. **Correlation Analysis**: The project calculates correlation coefficients between student admissions and various factors, including GDP growth, AI developments, new COVID-19 cases, and average salaries. The correlation coefficients provide insights into the strength and direction of relationships. 3. **Statistical Methods**: Various statistical methods are employed to analyze the data, including calculation of correlation coefficients to quantify the relationships between student admissions and the selected factors, and visualization techniques to present the data in an understandable format.

## Visualizations
The project generates several visualizations to illustrate the findings

## Results
The analysis reveals significant correlations between student admissions and various factors: **Admissions and GDP Growth**: Correlation coefficient of **0.1943** (Weak Positive Correlation). **Admissions and AI Developments**: Correlation coefficient of **-0.4935** (Moderate Negative Correlation). **Admissions and New COVID-19 Cases**: Correlation coefficient of **-0.5972** (Strong Negative Correlation). **Admissions and Salaries**: Correlation coefficient of **0.5597** (Moderate Positive Correlation). These findings suggest that while economic growth has a slight positive effect on admissions, the impact of AI developments and COVID-19 cases has been more pronounced, negatively affecting enrollment.


## Future Work
Future enhancements to this project may include: - Expanding the dataset to include more years or additional factors. - Implementing machine learning models to predict future admissions based on historical data. - Conducting a more granular analysis of specific fields of study and their correlation with job market trends.

## Acknowledgments
- Special thanks to the contributors and data sources that made this project possible. - Acknowledgment of all libraries & tools used in the project.

## Contact Information
For any inquiries or feedback, feel free to reach out: - **Prateek**: [kumarprateek1866@gmail.com](kumarprateek1866@gmail.com)

Thank you for your interest in the **Student Admissions Analysis** project! We hope you find the insights valuable.

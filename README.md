# Sleep Metrics Insights: Exploring Sleeo Health Patterns Through Data Mining and Analytics

## Project Description
This project aims to address sleeping-related issues by leveraging data mining and big data analytics techniques. Using a dataset containing information on sleep duration and lifestyle factors, we utilize AWS (EC2/AMI), Jupyter, PySpark, and Spark to perform in-depth analysis and derive meaningful insights.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Data Source](#data-source)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)


## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sleep-analysis-project.git

2. Set up a virtual environment and install the required dependencies:

```
cd sleep-analysis-project
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```
jupyter notebook
```

## Usage

Start your AWS EC2 instance using the provided AMI.

Connect to your EC2 instance and set up the necessary environment.

Open the Jupyter Notebook and follow the steps outlined in `Spark DataFrame Iteration4.ipynb`.

## Project Structure

```
INFOSYS722-BDAS/
│
├── .ipynb_checkpoints  //Checkpoints created by Jupyter Notebook
│
├── Datasets  //Datasets used for analysis
│
├── README.md
├── Sleep Metrics Insights: Exploring Sleeo Health Patterns Through Data Mining and Analytics.pdf  //Formal report summarizing the project's findings, methodology, and key insights
├── Spark DataFrame Iteration4.ipynb  //Main file for data analysis. Includes steps for cleaning, preprocessing, analyzing, and visualizing the data
└── Spark DataFrame Iteration4.1 re iteration.ipynb  //Re-iteration of data analysis with modified attributes based on feedback.
 
```

## Features
Data Processing: Clean and preprocess the sleep and lifestyle data.

Data Analysis: Perform exploratory data analysis using PySpark.

Reiteration: Update and refine analysis based on feedback.

Visualization: Visualize sleep patterns and lifestyle correlations.

Modeling: Build predictive and clustering models to identify factors influencing sleep quality.

## Data Source
The dataset used in this project is sourced from Kaggle[https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset] and includes detailed information on sleep duration and various lifestyle factors.

## Methodology
The methodology adopted involves eight steps synthesized from the Cross-Industry Standard Process for Data Mining (CRISP-DM) process (SPSS, 2007) and the KDD process (Fayyad et al., 1996). The steps include:

### Business/Situation Understanding: 
Identify the objectives, assess the situation, determine data mining objectives, and produce a project plan. A clear understanding ensures the research stays on track and provides valuable insights.

### Data Understanding: 
Collect initial data, describe the data, explore it at a surface level, and verify data quality to identify any missing values or errors.
Data Preparation: Select, clean, construct, integrate, and format the data. Proper data preparation ensures that the data used for analysis is clean, relevant, and suitable for the chosen analysis techniques.
### Data Transformation: 
Perform data reduction and projection. Convert or modify raw data into a suitable format for analysis and modeling. Feature selection and balancing the data are crucial steps in this phase.
### Data Mining Method Selection: 
Conduct thorough research to align with the study's objectives and identify the most suitable methodology. Consider factors such as data types, data mining goals, and special modeling requirements.
### Data Mining Algorithm Selection: 
Research and choose the most suitable algorithm for building the model. Ensure that the selected algorithm aligns with the study objectives, data types, and available resources.
### Data Mining: 
Construct statistical models using the selected algorithms. Partition the data into training and testing sets, implement the models through code, and identify trends and correlations.
### Interpretation: 
Discuss the results, models, and patterns to gain deeper insights. Evaluate the model's performance and conduct multiple iterations to ensure efficacy and resilience.

## Results
The results of the analysis, including key insights and visualizations, are detailed in the Formal Report and detailed steps are in the Jupyter Notebooks.

## Contributing
We welcome contributions from the community. Please fork the repository and create a pull request with your changes.










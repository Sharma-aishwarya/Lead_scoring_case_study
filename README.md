# Lead Scoring Project

This repository contains the code and analysis for the Lead Scoring project, which focuses on optimizing the lead conversion process for X Education, an online educational company.

## Project Overview
The objective of this project is to build a lead scoring model that effectively identifies potential customers with a higher likelihood of conversion. By prioritizing leads based on their conversion potential, X Education can streamline their sales efforts and improve the overall conversion rate.

## Model Summary
The lead scoring model is based on a logistic regression approach, utilizing 12 predictor variables. The model demonstrates a good fit, with a pseudo R-squared value of 0.3468. The selected features that contribute most to lead conversion probability are:

1. Do Not Email
2. Total Time Spent on Website
3. Lead Origin_Lead Add Form
4. Lead Source_Direct Traffic
5. Lead Source_Google
6. Lead Source_Organic Search
7. Lead Source_Reference
8. Lead Source_Referral Sites
9. What is your current occupation_Other
10. What is your current occupation_Student
11. What is your current occupation_Unemployed
12. What is your current occupation_Working Professional

These features play a crucial role in predicting lead conversion, and X Education should focus on leveraging them to maximize their sales potential.

## Model Evaluation
The model demonstrates a good level of accuracy, with an overall accuracy of 77.05%. The sensitivity (true positive rate) is 82.89%, indicating the model's ability to correctly identify positive instances (converted leads). The specificity (true negative rate) stands at 73.49%, reflecting the model's proficiency in identifying negative instances (non-converted leads).

## Recommendations
Based on the analysis and model findings, the following recommendations can be made:

1. Implement lead prioritization based on the identified important features to focus sales efforts on high-potential leads.
2. Pay attention to lead sources such as Direct Traffic, Google, Organic Search, and Referral Sites, as they contribute significantly to lead conversion.
3. Utilize Lead Add Forms as they exhibit a strong positive impact on lead conversion.
4. Target Working Professionals, Students, and individuals in Other occupations, as they show a higher likelihood of conversion.
5. Pay attention to factors such as Do Not Email and Total Time Spent on Website, as they significantly influence lead conversion probability.

By implementing these recommendations, X Education can enhance their lead conversion process and achieve improved sales performance.


## Repository Structure
The repository contains the following files and directories:

- `main.py`: The main Python file containing the code for data preprocessing, model training, and evaluation.
- `docs/`: This directory includes two Word documents in PDF format, providing detailed documentation and analysis of the project.
- `presentation/`: This directory contains a PDF presentation summarizing the project and its findings.
- `README.md`: The file you are currently reading, providing an overview and details about the project.

Feel free to adjust the details based on your actual file and folder structure.
## Usage
To reproduce the results and run the code in this repository, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/lead-scoring.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Explore the Jupyter notebooks in the `notebooks/` directory to understand the project workflow and execute the code cells.

Please refer to the Jupyter notebooks for a detailed analysis and step-by-step explanation of the lead scoring project.

## Conclusion
The Lead Scoring project provides X Education with a data-driven approach to prioritize leads and enhance their lead conversion process. By utilizing the identified important features and implementing the lead scoring model, X Education can focus their sales efforts on high-potential leads, leading to improved conversion rates and increased sales performance.
# Loan Lending Application Analysis
> This repository contains an end-to-end exploratory data analysis (EDA) for a consumer finance company specializing in lending various types of loans to urban customers. 
The goal of this project is to identify key risk factors associated with loan defaults and provide actionable insights to minimize credit losses.
Loan Risk Analysis for Consumer Finance lending company.EDA to understand how consumer attributes and loan attributes influence the tendency of default.


## Table of Contents
* [General Info](#general-information)
* [Analysis Overview](#analysis-overview)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [How To Run Project](#how-to-run-project)
* [Contact Me](#contact)


# General Information
The primary objective is to analyze loan applicant data and determine the factors that influence loan defaults, allowing the company to:
- Reduce financial losses by identifying risky applicants.
- Improve loan approval decisions.
- Understand the drivers behind loan defaults using EDA.


# 📊 **Analysis Overview**
### 1. **Business Understanding**
The company faces two primary risks:
- Approving loans for applicants likely to default, causing financial loss.
- Rejecting loans for applicants likely to repay, causing missed business opportunities.

### 2. **Data Exploration**
- The dataset contains various applicant-level features such as loan amount, purpose, term, interest rates, and repayment status.
- Key focus areas include:
  - Univariate Analysis
  - Bivariate Analysis
  - Risk Segmentation

### 3. **Insights**
#### Loan Status Distribution:
- Most loans are "Fully Paid."
- Significant defaults are observed in "Charged Off" loans.

#### Default Trends by Loan Term:
- Short-term loans (36 months) have lower default rates.
- Long-term loans (60 months) are riskier.

#### Interest Rate Analysis:
- Defaulters tend to have higher interest rates.

#### Loan Purpose Insights:
- Loans for debt consolidation and small businesses exhibit higher default rates.


# Technologies Used
 **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Plotly (if interactive visualizations are included)

# Conclusions
The following visualizations are included:
- Loan Status Distribution
- Interest Rate KDE Plot for Defaulters vs. Non-Defaulters
- Default Rate by Loan Term
- Loan Purpose and Default Trends
- Boxplots and Histograms for Risk Analysis


# 🚀 **How to Run**
1. Clone the repository:
   git clone https://github.com/nisha60dg/LendingClubCaseStudy.git
   git checkout main branch
   cd loan-lending-analysis
   jupyter notebook notebooks/ML69_Nisha_Pathania.ipynb


# Contact
Created by [@nisha60dg] - feel free to contact me!

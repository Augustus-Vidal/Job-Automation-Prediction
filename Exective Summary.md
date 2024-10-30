# Project Goal
    Our primary objective was to develop a predictive model capable of assessing the risk of automation within specific industries. By evaluating various job roles and industry characteristics, our model provides insights into which sectors and job types are most susceptible to automation. 

    This project is motivated by the rapid advances in technology and the potential for automation to reshape the employment landscape. With this model, stakeholders can anticipate and prepare for shifts in the labor market, prioritizing efforts to support industries and jobs most at risk.


# Key Findings
- High-Risk Industries: The model’s predictions reveal that certain industries—particularly manufacturing, retail, and administrative support—are at high risk for job displacement due to automation.

- Job Characteristics Influencing Risk: Jobs with repetitive tasks, low requirement for human creativity, and minimal social interaction are more likely to be automated.

- Impact of Automation on Employment: Our findings suggest that automation could significantly impact lower-skill roles, disproportionately affecting entry-level and manual positions. As a result, there may be substantial implications for workforce dynamics, income distribution, and training needs.

- Need for Proactive Planning: Given the potential for automation to disrupt jobs, proactive measures, such as upskilling initiatives and industry diversification, could help mitigate risks.


# Project Objectives
- Objective 1: Identify high-risk job categories within targeted industries.

- Objective 2: Analyze patterns and factors influencing automation vulnerability.

- Objective 3: Provide predictive insights into future industry changes due to automation.


# Data collection 
- Kaggle.com - “AI-Powered Job Market Insights”
- This dataset includes 500 unique job listings, each characterized by different factors like industry, company size, AI adoption level, automation risk, required skills, and job growth projections.

# Data Cleanup & Preparation
- Processes: When we brought our data in we noticed that we had no missing values in the dataset. We got lucky because we did not need to drop any columns or values because the data was all relevant for training our models. 

- Challenges: The biggest challenge we ran into was figuring out what model would work best with the dataset we had. We all tested a different type of model to compare and select which one worked best for us. 


# What did we do with our Model
We developed a input system using dropdown menus to streamline job automation risk predictions. This interface allows users to select key factors like job title, industry, salary range, and remote-friendliness. Each dropdown limits selections to values found in our dataset, ensuring consistency and data integrity. After users input their choices, the model processes these factors to output a prediction of automation likelihood.

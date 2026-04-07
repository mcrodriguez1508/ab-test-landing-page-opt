# ab-test-landing-page-opt
comprehensive A/B testing framework evaluating landing page variants, revenue impact, and traffic source efficiency using Python

A/B Testing Analysis: E-commerce Landing Page Optimization

📌 **Project Overview**
This project evaluates the performance of two different landing pages (Version A vs. Version B) for an e-commerce platform. The goal was to determine which version maximizes user conversion rates and average order value (AOV) using statistical hypothesis testing.

Through rigorous data analysis, I identified a clear "winner" and provided actionable insights regarding traffic sources and user behavior to optimize marketing spend.

📊 **Key Findings**
  - Conversion Rate: *Version B* outperformed *Version A* with a statistically significant increase (~15.9% vs ~12.5%).
  - Average Spending: Users on *Version B* spent significantly more per transaction (p<0.05).
  - Traffic Sources: Paid *Ads* and *Email* marketing showed higher conversion efficiency than organic traffic.
  - User Profiles: No significant difference was found between New and Returning users, suggesting the landing page design has a universal impact.

🛠️ **Technologies Used**
  - Python 3.x
  - Pandas & NumPy: Data cleaning and manipulation.
  - Matplotlib & Seaborn: Advanced data visualization.
  - SciPy & Statsmodels: Statistical testing (T-Test, Z-Test, Chi-Square).

🧪 **Statistical Methodology**
1. Revenue Analysis (T-Test)
   - $H₀$: No difference in average spending between A and B.
   - Result: Rejected H₀ (p=0.0000). Version B generates higher revenue per user.
2. Conversion Rate (Z-Test for Proportions)
   - H₀: Conversion rates for A and B are equal.
   - Result: Rejected H₀ (p=0.0000). Version B is more effective at driving sales.
3. Categorical Associations (Chi-Square)
   - Traffic Source: Significant association (p=0.0341). Origin matters for conversion.
   - User Type: No significant association (p=0.4736). Performance is consistent across user segments.

📈 **Visualizations**
The project includes several key plots:
  - Stacked Bar Charts: Comparing absolute volumes vs. relative proportions for conversion.
  - Distribution Plots: Visualizing spending behavior across groups.

💡 **Business Recommendations**
  - Full deployment: Replace *Version A* with *ersion B* to maximize ROI.
  - Budget allocation: Increase investment in *Ads* and *Email* channels.
  - Unified Strategy: Maintain a consistent UI for both new and returning users as their conversion behavior is nearly identical.

📂 **Project Structure**
Plaintext

├── data/                   # Dataset (CSV)
├── notebooks/              # Jupyter Notebook with full analysis
├── README.md               # Project documentation
└── requirements.txt        # Necessary libraries

🚀 **How to Run**

Project Structure
Plaintext

├── data/                               # Dataset (CSV)
├── S9_Project_Landing_Experiment_MCRC.ipynb  # Main Analysis Notebook
├── README.md                           # Project documentation
└── requirements.txt                    # Necessary libraries

🚀 How to Run

    Clone the repository:
    Bash

    git clone https://github.com/mcrodriguez1508/ab-test-landing-page-opt.git

    Navigate to the project folder:
    Bash

    cd ab-test-landing-page-opt

    Install dependencies:
    Bash

    pip install -r requirements.txt

    Open the Jupyter Notebook:
    Bash

    jupyter notebook S9_Project_Landing_Experiment_MCRC.ipynb

Author: María Camila Rodríguez Cruz

Field: Data Analytics / Data Science

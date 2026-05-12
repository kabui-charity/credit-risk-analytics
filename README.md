### EXECUTIVE SUMMARY
Digital lending startups wants to extend its loan services to informal traders such as mama mbogas but they do not have bank accounts or credit histories with CRB, thus the company ends up rejecting almost 60% of the applicants.
The goal is to have alternative credit scoring model to safely lend the unbanked segment without spiking the non performing loan (NLP) ratio.
This will increase loan approval rates by 15% while keeping defaults below 5%.

### BUSINESS PROBLEM
Optimizing financial inclusion while reducing default risk is essential to FinTech industries.
A startup that wants to provide working capital loans to mama mbogas and small scale kiosk finds it hard to do so as these traders have no formal credit history.
They end up using gut feeling manual approval process, leading to a high default rate and slow scaling.
How can we use non traditional data such as airtime usage and mobile money velocity to automate loan approvals while dropping the default rate?

### METHODOLOGY
1. Data simulation in python
2. Exploratory data analysis
3. Model training, evaluation

### SKILLS
Python: pandas, matplotlib, numpy, seaborn,

### RESULTS
The exploratory data analysis confirms a highly balanced target distribution, ensuring the model was trained on a representative sample without majority bias.

<img width="550" height="402" alt="image" src="https://github.com/user-attachments/assets/7202f778-8444-46e6-b946-2920248ed763" />

Despite using a Random Forest Algorithm, the model achieved an accuracy of 55% with a low recall of 0.46 for defaults indicating that features such as airtime spend overlap between the classes such that they can not distinguish credit risk.
### BUSINESS RECOMMENDATIONS
Future analysis should be based on consistency based metrics such as frequency in mpesa inflow rather than volume based metrics such as total airtime spend to better capture the financial discipline and behaviour of the informal entrepreneur
To improve the model's precision, its better to integrate alternative data points such as utility payment history or geographic business density.

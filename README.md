\# Insurance Portfolio and Risk Analysis Project



This project focuses on evaluating 5,000 active insurance customer records to understand and solve major operational issues affecting modern insurance companies. Specifically, this analysis investigates customer cancellations (churn), high-risk claims patterns, digital platform adoption across age brackets, and regional profitability.



\---



\## Executive Summary of Business Findings



\### 1. Revenue Balance (Total Premiums Collected)

\* \*\*Context:\*\* A healthy insurance company should have a balanced mix of products so that a sudden downturn in one market doesn't break the entire business.

\* \*\*Findings:\*\* The portfolio shows an excellent, even split across all three insurance types, bringing in a total revenue of roughly $9.99 million.

&#x20; \* \*\*Auto Insurance:\*\* $3,453,631.05 (Our largest revenue driver)

&#x20; \* \*\*Life Insurance:\*\* $3,379,355.55

&#x20; \* \*\*Home Insurance:\*\* $3,158,135.14



\### 2. The Customer Retention Problem (Churn Rates)

\* \*\*Context:\*\* It costs a significant amount of marketing budget to win a new policyholder. If customers drop their policies early, the company loses money on those acquisition costs.

\* \*\*Findings:\*\* The company is currently facing a critical retention issue. Nearly half of all customers are actively cancelling their policies across the board:

&#x20; \* \*\*Life Churn:\*\* 48.78% (Highest cancellation rate)

&#x20; \* \*\*Home Churn:\*\* 48.34%

&#x20; \* \*\*Auto Churn:\*\* 47.63%

\* \*\*Takeaway:\*\* Management needs to urgently review customer onboarding, policy pricing, and service quality to stop this massive loss of business.



\### 3. Claims Pricing Accuracy (High-Risk Profile Performance)

\* \*\*Context:\*\* Underwriters use risk scores to price policies. Customers with high risk scores should be paying higher premiums to offset the cost of their claims.

\* \*\*Findings:\*\* The data proves that high-risk customers are heavily driving up company costs:

&#x20; \* \*\*Low/Medium Risk Profiles:\*\* $11,415.90 average claim payout

&#x20; \* \*\*High Risk Profiles (Risk Score > 80):\*\* $16,213.55 average claim payout

\* \*\*Takeaway:\*\* High-risk clients result in a 42% jump in average claim costs. Our pricing models must be tightened, and surcharges for high-risk applicants need to be increased immediately.



\### 4. Administrative Cost Savings (Digital App Adoption)

\* \*\*Context:\*\* Managing paper statements and manual call centers is incredibly expensive. Getting customers to use our mobile app dramatically drops administrative costs.

\* \*\*Findings:\*\* There is a heavy generational gap in how our customers interact with us:

&#x20; \* \*\*Young Adults (18-30):\*\* 75.87% application usage

&#x20; \* \*\*Mid-Age (31-50):\*\* 59.03% application usage

&#x20; \* \*\*Seniors (51+):\*\* 40.04% application usage

\* \*\*Takeaway:\*\* To realize actual cost savings, the digital product team needs to simplify the app interface and design targeted campaigns to help users over 50 comfortably use our digital tools.



\### 5. Regional Profitability (Claims-to-Premium Loss Ratio)

\* \*\*Context:\*\* For an insurance company to make money in a specific state, the total claims paid out must be lower than the premiums collected (a ratio under 1.0x).

\* \*\*Findings:\*\* Every single state we operate in is currently losing money, paying out far more in claims than we pull in from customer premiums:

&#x20; \* \*\*New York (NY):\*\* Pays out 1.87x its collected revenue in claims (Worst-performing state)

&#x20; \* \*\*Pennsylvania (PA):\*\* Pays out 1.66x its collected revenue in claims

&#x20; \* \*\*California (CA):\*\* Pays out 1.62x its collected revenue in claims

&#x20; \* \*\*Illinois (IL):\*\* Pays out 1.33x its collected revenue in claims (Lowest loss ratio, but still unprofitable)

\* \*\*Takeaway:\*\* The company is losing money rapidly on a national scale. Executives need to raise premium floors or consider pulling back our market footprint in heavy deficit states like NY, PA, and CA.



\---



\## Project Folder Structure



\* `data/`: Contains the master spreadsheet (`insurance\_data.csv`) consisting of 5,000 unique customer rows.

\* `notebooks/01\_Data\_Generation.ipynb`: The Jupyter Notebook used to build the synthetic dataset and embed realistic industry issues.

\* `notebooks/02\_Insurance\_Analysis.ipynb`: The notebook containing the logic and calculations used to answer the five business questions.



\---



\## How to Run This Project Locally



To run this data project on your own device:



1\. Download or clone this folder structure to your computer.

2\. Open \*\*Anaconda Navigator\*\* and launch \*\*Jupyter Notebook\*\*.

3\. Ensure you have `pandas` and `numpy` installed.

4\. Run the data generation notebook first to create the spreadsheet, then open the analysis notebook to see the data outputs.




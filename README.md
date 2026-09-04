<h1>📊 Telecom Customer Churn Analysis</h1>

<h2>📌 Project Overview</h2>

<p>
This project analyzes customer churn in a telecom company using
<b>SQL and Power BI</b>. The goal is to identify major churn patterns,
understand high-risk customer segments, and provide actionable business
recommendations for customer retention.
</p>

<h2>🎯 Business Objective</h2>

<ul>
  <li>Analyze overall customer churn</li>
  <li>Identify high-risk customer segments</li>
  <li>Understand churn across tenure, contract type, payment method, CLTV, and customer profile</li>
  <li>Identify key factors and patterns associated with customer churn</li>
  <li>Provide data-driven recommendations for customer retention</li>
</ul>

<h2>🗂️ Dataset</h2>

<p>
<b>Dataset:</b> Telco Customer Churn – IBM Dataset<br>
<b>Source:</b> Kaggle
</p>

<p>
The dataset contains customer demographics, services, contracts, payments,
tenure, charges, churn status, churn reasons, and CLTV information.
</p>

<h2>🛠️ Tools & Technologies</h2>

<ul>
  <li><b>SQL</b> – Data cleaning, validation and analysis</li>
  <li><b>Power BI</b> – Data modeling, DAX and dashboard development</li>
  <li><b>Power Query</b> – Data transformation</li>
  <li><b>Excel/CSV</b> – Initial data handling</li>
</ul>

<h2>🧹 Data Cleaning & Validation</h2>

<p>
The raw dataset was loaded into SQL and checked for:
</p>

<ul>
  <li>Duplicate records</li>
  <li>NULL and blank values</li>
  <li>Inconsistent values</li>
  <li>Data types and ranges</li>
  <li>Business logic validation</li>
</ul>

<p>
Blank <code>Total Charges</code> values for customers with zero tenure
were treated as valid business cases.
</p>

<h2>🗄️ Data Modeling</h2>

<p>
The data was transformed and structured for analysis in Power BI.
Relevant customer, service, contract, payment, churn, and CLTV attributes
were connected through appropriate relationships to support interactive
analysis.
</p>

<h2>📊 Dashboard</h2>

<p>The Power BI dashboard covers:</p>

<ul>
  <li><b>Executive Summary</b></li>
  <li><b>Customer Churn Analysis</b></li>
  <li><b>Customer & CLTV Analysis</b></li>
  <li><b>Churn Insights & Recommendations</b></li>
</ul>

<h2>🔍 Key Insights</h2>

<ul>
  <li>Month-to-month customers showed higher churn compared with customers on longer-term contracts.</li>
  <li>Customers with lower tenure were more likely to churn.</li>
  <li>Certain payment methods showed higher churn rates.</li>
  <li>High-CLTV customers were also present among churned customers, highlighting the importance of prioritizing valuable customers for retention.</li>
  <li>Churn varied across customer profiles and subscribed services.</li>
  <li>Churn reasons helped identify specific areas where customer experience and service offerings could be improved.</li>
</ul>

<h2>💡 Recommendations</h2>

<ul>
  <li>Encourage month-to-month customers to move toward longer-term contracts through targeted offers.</li>
  <li>Strengthen onboarding and early-stage engagement for new customers.</li>
  <li>Prioritize high-CLTV customers for proactive retention campaigns.</li>
  <li>Improve the payment experience for segments showing higher churn.</li>
  <li>Use customer characteristics, services, and churn reasons to design targeted retention strategies.</li>
</ul>

<h2>🔄 Project Workflow</h2>

<p>
<b>
SQL → Data Cleaning & Validation → SQL Analysis → Power Query
→ Data Modeling → DAX → Power BI Dashboard → Insights & Recommendations
</b>
</p>

<h2>📌 Conclusion</h2>

<p>
This project demonstrates an end-to-end <b>Data Analyst workflow</b>
using SQL and Power BI to analyze customer churn, identify high-risk
customer segments, understand churn patterns, and generate actionable
business recommendations for customer retention.
</p>

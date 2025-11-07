# home-loan-analysis-powerbi

# PowerBI Project ( Home Loan Analysis Dashboard )


<img width="988" height="740" alt="Screenshot 2025-11-07 105844" src="https://github.com/user-attachments/assets/943d5fb8-5456-4c52-8c7b-388e495c45dc" />



**1. Overview**

The Home Loan Analysis Dashboard provides a comprehensive view of loan performance metrics, enabling data-driven decisions for improving loan disbursement efficiency and recovery performance. It consolidates data from multiple channels, products, and regions to highlight the key drivers of loan applications, sanctions, disbursements, and recoveries across all branches.

**2. Key Metrics**

• Total No. of Customers: 25K

• Total Loan Applied: 245K

• Total Sanction Amount: 212.73K

• Total Disbursement Amount: 195.71K

• Total Recovery Amount: 104.20K

**3. Key Insights**

• The organization has processed over 245K loan applications, demonstrating strong customer acquisition efforts.

• A total of 25K customers are currently served, with strong engagement across multiple channels such as Direct Sales Agents, Online, and Walk-in customers.

• The total loan sanctioned (212.73K) is approximately 86% of total loan applied, indicating a healthy approval rate.

• The disbursement (195.71K) and recovery (104.20K) amounts show effective financial follow-up and loan processing efficiency.

• Trend analysis by year and month shows steady loan application growth from 2017 to 2019, with notable peaks likely corresponding to seasonal promotions or   financial cycles.

• Product-wise distribution highlights Group Loans, Top-up Loans, and Individual Loans as the top contributing categories.

• Branch performance analysis indicates consistent loan distribution across multiple branches, with some high-performing branches exceeding 1.7K customers.

• Geographic mapping reveals a strong footprint across India and nearby regions, suggesting successful market expansion.

**4. DAX Measures**

• Total Loan Applied = SUM(Loan[AppliedAmount])

• Total Sanction Amount = SUM(Loan[SanctionAmount])

• Total Disbursement Amount = SUM(Loan[DisbursedAmount])

• Total Recovery Amount = SUM(Loan[RecoveryAmount])

• Approval Rate % = DIVIDE([Total Sanction Amount], [Total Loan Applied], 0) * 100

• Disbursement Rate % = DIVIDE([Total Disbursement Amount], [Total Sanction Amount], 0) * 100

• Recovery Efficiency % = DIVIDE([Total Recovery Amount], [Total Disbursement Amount], 0) * 100

**5. Slicer Interaction**

The dashboard incorporates slicers for Gender (Male, Female, Third Gender) and Branch Name. These allow users to dynamically filter visuals and focus on specific 
demographic or regional segments. For example, selecting 'Female' in the gender slicer instantly updates all charts and KPIs to reflect loans applied and sanctioned by female customers.

**6. Conditional Formatting**

Conditional formatting was applied to key visuals such as bar charts and KPIs. For example, higher performance metrics (e.g., top branches or loan disbursements) are displayed in darker shades of blue, while lower values appear in lighter tones. This gradient visualization helps identify strong and weak performing areas at a glance.

**7. Conclusion**

The Home Loan Analysis Dashboard serves as a strategic monitoring tool, providing an end-to-end view of the loan lifecycle. It highlights strengths in customer acquisition, loan sanctioning, and recovery processes. With geographic insights, channel-based segmentation, and KPI-driven analysis, management can identify high-performing regions and optimize loan operations. The inclusion of DAX-based measures ensures dynamic and accurate reporting, promoting informed financial decisions.

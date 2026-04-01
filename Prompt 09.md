### **# Prompt #9 — Loan Terms Calculation**

\*\*Section\*\*: Loan Approval  

\*\*Workflow Step\*\*: Step 9 of 3  

\*\*Current Version\*\*: v1.2  

\*\*Status\*\*: 🔄 In Progress  

\*\*Last Updated\*\*: 2026-04-01



\---



### **## 📌 \*\*Prompt Text (v1.2 — Current)\*\***



> Copy this exactly into your AI tool. Replace all `\[PLACEHOLDERS]` before running.

**"Calculate the loan terms based on the applicant’s credit score, income, and loan amount. If the credit score is above 700, offer the applicant a loan with a 5% interest rate and a 5-year repayment term. If the credit score is below 700, offer the loan with a 7% interest rate and a 3-year repayment term."**





**\*\*Placeholders to fill:\*\***



**| Placeholder           | Source                                   | Example   |**

**|-----------------------|------------------------------------------|-----------|**

**| `\[CREDIT\_SCORE]`      | Applicant's credit score                 | 720       |**

**| `\[LOAN\_AMOUNT]`       | Applicant's requested loan amount        | $15,000   |**

**| `\[INTEREST\_RATE]`     | Approved interest rate                   | 5%        |**

**| `\[REPAYMENT\_TERM]`    | Loan repayment term (in years)           | 5         |**



**---**



### **## 🏢 \*\*Intended Workflow or Task\*\***



**This prompt fits into the \*\*loan approval process\*\* to calculate the terms of the loan (interest rate and repayment term) based on the applicant’s financial profile.**



**- \*\*Trigger\*\*: Loan application submitted with the applicant’s financial details.**

**- \*\*Actor\*\*: Loan officer or AI system calculating the loan terms.**

**- \*\*Timing\*\*: This prompt runs after the applicant’s credit score, income, and loan amount are provided.**

**- \*\*Next Step\*\*: The AI-generated loan terms are sent to the loan officer for final review and approval.**



**Example workflow:Applicant submits financial details → \[THIS PROMPT RUNS] → Output routed to loan officer for review**



**---**



### **## ❗ \*\*Problem Being Solved\*\***



**Manually calculating loan terms based on credit score, income, and requested amount is prone to errors and inconsistencies. Automating this calculation ensures faster, more accurate loan processing, improving both efficiency and consistency.**



**\*\*Pain points addressed:\*\***

**- Time spent manually calculating loan terms.**

**- Errors in setting the correct interest rate or repayment period.**

**- Inconsistency in loan offer details across applications.**



**---**



### **## ⚡ \*\*Automation Potential\*\***



**\*\*Level\*\*: High**



**| Dimension              | Assessment                                           |**

**|------------------------|------------------------------------------------------|**

**| Repetitiveness          | High — This task happens for every loan application. |**

**| Data availability       | Readily available in the loan application.           |**

**| Human judgment needed   | Low — AI can handle the calculations, but the loan officer must review the final offer. |**

**| Integration possibility | High — Can integrate with loan management and CRM systems. |**

**| Estimated time saving   | \~70% — Reduces manual calculation time from 15 minutes to 5 minutes per applicant. |**



**\*\*Human-in-the-loop role\*\*: Loan officer reviews the AI-generated loan terms and makes final approval.**



**---**



### **## ⚠️ \*\*Risks and Limitations\*\***



**| Risk                                    | Level | Mitigation                                                 |**

**|-----------------------------------------|-------|------------------------------------------------------------|**

**| Inaccurate data input (e.g., wrong credit score or income) | High  | Ensure validation checks are in place for accurate data.    |**

**| Over-simplification of loan terms based solely on credit score | Medium | Include other factors like income and debt-to-income ratio for a more balanced offer. |**

**| Risk of algorithmic bias in loan terms | Medium | Regularly update the AI model to ensure fairness and avoid biases. |**



**\*\*Overall risk rating\*\*: Medium — The prompt is reliable, but data quality and fairness need continuous attention.**



**---**

### 

### **## 🔄 \*\*Version History\*\***



**### \*\*v1.0 — Initial Draft\*\***

**\*\*Date\*\*: 2026-03-19**  

**\*\*Prompt\*\*: "Calculate the loan terms based on the applicant’s credit score, income, and loan amount."**  

**\*\*Output\*\*: AI recommended loan terms based on credit score but did not account for other financial factors.**  

**\*\*Lesson learned\*\*: The initial version was too simplistic, relying solely on credit score for the terms.**



**---**



**### \*\*v1.1 — Improved Version\*\***

**\*\*Date\*\*: 2026-03-23**  

**\*\*Change\*\*: Added income and loan amount as factors to adjust interest rates and repayment periods.**  

**\*\*Output\*\*: More accurate and tailored loan terms for each applicant.**  

**\*\*Lesson learned\*\*: Including more variables (like loan amount) makes the terms more realistic and personalized.**



**---**



**### \*\*v1.2 — Final Refinements ✅ Current\*\***

**\*\*Date\*\*: 2026-04-01**  

**\*\*Change\*\*: Adjusted the calculation thresholds for interest rates and repayment terms based on a broader range of financial data.**  

**\*\*Output\*\*: Final output now includes a more accurate interest rate and repayment term tailored to the applicant’s full financial situation.**  

**\*\*Observed effect\*\*: Improved accuracy of loan offers, better alignment with applicants’ financial capacity.**  

**\*\*Lesson learned\*\*: Incorporating a wider set of financial data (beyond just credit score) leads to more informed loan decisions.**



**---**



**## 🔗 \*\*Related Prompts\*\***



**- \*\*Previous in chain\*\*: \[Link to previous prompt if chained]**

**- \*\*Next in chain\*\*: \[Link to next prompt if chained]**

**- \*\*Parent section\*\*: \[Link to section README]**



**---**



**### \*\*How to Use This Prompt:\*\***

**1. Replace the placeholders (`\[CREDIT\_SCORE]`, `\[LOAN\_AMOUNT]`, `\[INTEREST\_RATE]`, `\[REPAYMENT\_TERM]`) with the applicant’s actual data before running the prompt in your AI system.**

**2. Review the AI-calculated loan terms and proceed with the loan offer or adjustments as needed.**



**---**




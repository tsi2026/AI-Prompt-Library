\# Prompt #4 — Risk Assessment Based on Past Defaults

\*\*Section\*\*: Loan Approval  

\*\*Workflow Step\*\*: Step 4 of 3  

\*\*Current Version\*\*: v1.0  

\*\*Status\*\*: 🔄 In Progress  

\*\*Last Updated\*\*: 2026-04-01



\---



\## 📌 \*\*Prompt Text (v1.0 — Current)\*\*



> Copy this exactly into your AI tool. Replace all `\[PLACEHOLDERS]` before running.



**"You are a loan officer. Assess the risk level of the applicant based on their past loan defaults or late payments. Assign a risk score (low, medium, high) based on historical data. If the applicant has more than two defaults in the past five years, assign a high-risk score."**





\*\*Placeholders to fill:\*\*



| Placeholder           | Source                                   | Example   |

|-----------------------|------------------------------------------|-----------|

| `\[DEFAULTS]`          | Number of loan defaults in the past five years | 3         |

| `\[PAYMENT\_HISTORY]`   | Applicant's payment history              | Late 2 times |

| `\[RISK\_SCORE]`        | Assigned risk score (low, medium, high)  | High      |



\---



### **## 🏢 \*\*Intended Workflow or Task\*\***



This prompt fits into the \*\*loan approval process\*\* to evaluate the applicant’s risk based on past loan defaults, helping to assess the likelihood of future default.



\- \*\*Trigger\*\*: Applicant’s loan application is received and payment history is available.

\- \*\*Actor\*\*: Loan officer or AI system reviewing the applicant’s financial history.

\- \*\*Timing\*\*: This prompt runs after the applicant’s credit score and income verification.

\- \*\*Next Step\*\*: AI-generated risk score is passed to the loan officer for final approval.



**Example workflow:Applicant submits loan application → \[THIS PROMPT RUNS] → Output routed to loan officer for review**





**---**



### **## ❗ \*\*Problem Being Solved\*\***



**Assessing the applicant’s risk of default based on past behavior is currently done manually and may not account for all relevant factors. This prompt automates the risk assessment process, ensuring consistent, data-driven evaluations.**



**\*\*Pain points addressed:\*\***

**- Time spent manually reviewing past defaults.**

**- Risk of human error in assessing historical payment behavior.**

**- Inconsistent risk assessment criteria.**



**---**



### **## ⚡ \*\*Automation Potential\*\***



**\*\*Level\*\*: Medium**



**| Dimension              | Assessment                                           |**

**|------------------------|------------------------------------------------------|**

**| Repetitiveness          | High — This task happens for every loan application. |**

**| Data availability       | Readily available from applicant’s credit report and history. |**

**| Human judgment needed   | Medium — AI can assign a risk score, but loan officer must review it for final approval. |**

**| Integration possibility | Medium — Can integrate with loan management systems, but may require manual input for some data. |**

**| Estimated time saving   | \~30% — Reduces manual review time from 20 minutes to 14 minutes per applicant. |**



**\*\*Human-in-the-loop role\*\*: Loan officer reviews AI-generated risk score and considers additional contextual factors before making a final decision.**



**---**



### **## ⚠️ \*\*Risks and Limitations\*\***



**| Risk                                    | Level | Mitigation                                                 |**

**|-----------------------------------------|-------|------------------------------------------------------------|**

**| Incomplete or inaccurate historical data (e.g., missing payment records) | High  | Ensure data completeness before processing.                |**

**| Over-reliance on historical data without considering current financial situation | Medium | Use supplementary data (e.g., current income, employment status) for a balanced decision. |**

**| Bias in historical data leading to unfair risk assignments | Medium | Regularly update the AI model and ensure fair evaluation of all applicants. |**



**\*\*Overall risk rating\*\*: Medium — The process is reliable but needs careful validation of data and ongoing oversight.**



**---**



### **## 🔄 \*\*Version History\*\***



**### \*\*v1.0 — Initial Draft\*\***

**\*\*Date\*\*: 2026-03-19**  

**\*\*Prompt\*\*: "Assess the risk of the applicant based on their past loan defaults and payment history."**  

**\*\*Output\*\*: AI recommended high-risk scores for applicants with multiple defaults.**  

**\*\*Lesson learned\*\*: Initial version was too rigid, considering only defaults without accounting for other factors like recent improvements in financial behavior.**



**---**



**### \*\*v1.1 — Improved Version\*\***

**\*\*Date\*\*: 2026-03-23**  

**\*\*Change\*\*: Introduced additional context such as late payments and recent financial behavior.**  

**\*\*Output\*\*: AI now assigns a more accurate risk score considering multiple financial indicators.**  

**\*\*Lesson learned\*\*: Adding more data points improves the overall accuracy of the risk assessment.**



**---**



**### \*\*v1.2 — Final Refinements ✅ Current\*\***

**\*\*Date\*\*: 2026-04-01**  

**\*\*Change\*\*: Adjusted risk scoring thresholds and added more nuanced evaluation factors like income and current financial status.**  

**\*\*Output\*\*: Final output is more balanced and reflects a broader view of the applicant’s financial health.**  

**\*\*Observed effect\*\*: Improved accuracy in risk scoring, leading to better-informed loan decisions.**  

**\*\*Lesson learned\*\*: A more holistic view of the applicant’s financial situation leads to more fair and accurate risk assessment.**



**---**



**## 🔗 \*\*Related Prompts\*\***



**- \*\*Previous in chain\*\*: \[Link to previous prompt if chained]**

**- \*\*Next in chain\*\*: \[Link to next prompt if chained]**

**- \*\*Parent section\*\*: \[Link to section README]**



**---**



**### \*\*How to Use This Prompt:\*\***

**1. Replace the placeholders (`\[DEFAULTS]`, `\[PAYMENT\_HISTORY]`, `\[RISK\_SCORE]`) with the applicant’s actual data before running the prompt in your AI system.**

**2. Review the AI-generated risk score and decide on loan approval or rejection based on the evaluation.**



**---**




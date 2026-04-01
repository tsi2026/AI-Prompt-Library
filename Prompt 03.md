### **# Prompt #3 — Loan Type Recommendation**

\*\*Section\*\*: Loan Approval  

\*\*Workflow Step\*\*: Step 3 of 3  

\*\*Current Version\*\*: v1.2  

\*\*Status\*\*: 🔄 In Progress  

\*\*Last Updated\*\*: 2026-04-01



\---

### 

### **## 📌 \*\*Prompt Text (v1.2 — Current)\*\***



> Copy this exactly into your AI tool. Replace all `\[PLACEHOLDERS]` before running.



"Based on the applicant’s credit score, income, and debt-to-income ratio, suggest the most suitable loan type (e.g., personal loan, mortgage, auto loan). Recommend a personal loan if the credit score is below 650, and a mortgage if the credit score is above 700."



**\*\*Placeholders to fill:\*\***



| Placeholder           | Source                                   | Example   |

|-----------------------|------------------------------------------|-----------|

| `\[CREDIT\_SCORE]`      | Applicant's credit score                 | 680       |

| `\[INCOME]`            | Applicant's income                       | $55,000   |

| `\[DEBT\_TO\_INCOME]`    | Applicant's debt-to-income ratio         | 35%       |



\---

### 

### **## 🏢 \*\*Intended Workflow or Task\*\***



This prompt is part of the \*\*loan approval process\*\* to recommend the most suitable loan type for the applicant based on their financial profile.



\- \*\*Trigger\*\*: Loan officer or AI system receives the applicant’s credit score, income, and debt-to-income ratio.

\- \*\*Actor\*\*: Loan officer or AI system reviewing the applicant’s financial details.

\- \*\*Timing\*\*: This prompt runs after credit evaluation and income verification.

\- \*\*Next Step\*\*: The AI recommendation is passed to the loan officer for final approval.



**Example workflow:Applicant submits income documentation → \[THIS PROMPT RUNS] → Output routed to loan officer for review**



**---**

### 

### **## ❗ \*\*Problem Being Solved\*\***



**Verifying income manually is time-consuming and can lead to inconsistencies in how applicants' financial capacity is assessed. This automation speeds up the process, reduces errors, and ensures that loan eligibility decisions are based on up-to-date, consistent data.**



**\*\*Pain points addressed:\*\***

**- Time spent manually verifying income documents.**

**- Risk of errors or oversight when reviewing multiple documents.**

**- Delays in loan approval due to inefficient manual verification.**



**---**



### **## ⚡ \*\*Automation Potential\*\***



**\*\*Level\*\*: High**



**| Dimension              | Assessment                                           |**

**|------------------------|------------------------------------------------------|**

**| Repetitiveness          | High — This task happens for every loan application. |**

**| Data availability       | Readily available in applicant’s submitted documents. |**

**| Human judgment needed   | Medium — AI can verify income but loan officer must approve the final recommendation. |**

**| Integration possibility | Medium — Can integrate with loan management systems but requires data import from external sources. |**

**| Estimated time saving   | \~50% — Reduces manual review time from 30 minutes to 15 minutes per application. |**



**\*\*Human-in-the-loop role\*\*: Loan officer verifies AI’s income recommendation before making final approval.**



**---**



### **## ⚠️ \*\*Risks and Limitations\*\***



**| Risk                                    | Level | Mitigation                                                 |**

**|-----------------------------------------|-------|------------------------------------------------------------|**

**| Data inconsistency (e.g., missing or incorrect income data) | High  | Ensure income data is complete and validated before processing. |**

**| AI might miss out on some contextual factors (e.g., irregular income sources) | Medium | Use supplementary data to verify applicant’s full financial situation. |**

**| Privacy concerns when handling sensitive financial documents | High  | Ensure compliance with data protection regulations (e.g., GDPR). |**



**\*\*Overall risk rating\*\*: Medium — The process is reliable but needs careful data handling and validation.**



**---**



### **## 🔄 \*\*Version History\*\***



**### \*\*v1.0 — Initial Draft\*\***

**\*\*Date\*\*: 2026-03-19**  

**\*\*Prompt\*\*: "Verify the income of the applicant by comparing the submitted financial documents with the income thresholds."**  

**\*\*Output\*\*: AI suggested loan approval based on income but lacked deeper validation for different income sources.**  

**\*\*Lesson learned\*\*: The initial version didn’t fully account for applicants with irregular income streams.** 



**---**



**### \*\*v1.1 — Improved Version\*\***

**\*\*Date\*\*: 2026-03-23**  

**\*\*Change\*\*: Added context for varying income types (e.g., freelance, contract work).**  

**\*\*Output\*\*: AI now accounts for different employment types and sources of income.**  

**\*\*Lesson learned\*\*: Including more details about employment type improves accuracy in recommendations.**



**---**



**### \*\*v1.2 — Final Refinements ✅ Current\*\***

**\*\*Date\*\*: 2026-04-01**  

**\*\*Change\*\*: Added a specific income threshold based on employment type to enhance decision-making.**  

**\*\*Output\*\*: Final output is more consistent, with clearer guidelines on income verification.**  

**\*\*Observed effect\*\*: Improved consistency and reduced manual follow-up required.**  

**\*\*Lesson learned\*\*: Defining a clear income threshold based on job type makes the process more reliable.**



**---**





**## 🔗 \*\*Related Prompts\*\***



**- \*\*Previous in chain\*\*: \[Link to previous prompt if chained]**

**- \*\*Next in chain\*\*: \[Link to next prompt if chained]**

**- \*\*Parent section\*\*: \[Link to section README]**



**---**



**### \*\*How to Use This Prompt:\*\***

**1. Replace the placeholders (`\[INCOME]`, `\[EMPLOYMENT\_TYPE]`, `\[INCOME\_THRESHOLD]`) with the applicant’s actual data before running the prompt in your AI system.**

**2. Review the AI’s recommendation, and proceed with loan approval or rejection based on the income verification.**



**---**




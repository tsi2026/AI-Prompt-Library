### **# Prompt 02 — Income Verification**



\*\*Section\*\*: Loan Approval  

\*\*Workflow Step\*\*: Step 2 of 3  

\*\*Current Version\*\*: v1.0  

\*\*Status\*\*: 🔄 In Progress  

\*\*Last Updated\*\*: 2026-04-01



\---



### **## 📌 \*\*Prompt Text (v1.2 — Current)\*\***



> Copy this exactly into your AI tool. Replace all `\[PLACEHOLDERS]` before running.



"You are a loan officer. Verify the income of the applicant by comparing the submitted financial documents (e.g., pay stubs, tax returns) with the income thresholds based on their employment type. If the income exceeds the threshold, recommend loan approval."





**\*\*Placeholders to fill:\*\***



| Placeholder           | Source                                   | Example   |

|-----------------------|------------------------------------------|-----------|

| `\[INCOME]`            | Applicant's declared income              | $50,000   |

| `\[EMPLOYMENT\_TYPE]`   | Applicant's job type (full-time, part-time, etc.) | Full-time |

| `\[INCOME\_THRESHOLD]`  | Set income threshold for loan approval   | $45,000   |



\---

### 

### **## 🏢 \*\*Intended Workflow or Task\*\***



This prompt fits into the \*\*loan approval process\*\*, specifically for verifying the applicant's income to assess their eligibility for a loan.



**- \*\*Trigger\*\*:** Applicant submits income documentation (e.g., pay stubs, tax returns).

**- \*\*Actor\*\*:** Loan officer or AI system reviewing the submitted income data.

**- \*\*Timing\*\*:** This prompt runs immediately after the applicant’s income details are provided.

**- \*\*Next Step\*\*:** AI recommendation for loan approval is sent to the loan officer for further review.



**Example workflow: Applicant submits income documentation → \[THIS PROMPT RUNS] → Output routed to loan officer for review**



\---



### **## ❗ \*\*Problem Being Solved\*\***



Verifying income manually is time-consuming and can lead to inconsistencies in how applicants' financial capacity is assessed. This automation speeds up the process, reduces errors, and ensures that loan eligibility decisions are based on up-to-date, consistent data.



\*\*Pain points addressed:\*\*

\- Time spent manually verifying income documents.

\- Risk of errors or oversight when reviewing multiple documents.

\- Delays in loan approval due to inefficient manual verification.



\---



### **## ⚡ \*\*Automation Potential\*\***



\*\*Level\*\*: High



| Dimension              | Assessment                                           |

|------------------------|------------------------------------------------------|

| Repetitiveness          | High — This task happens for every loan application. |

| Data availability       | Readily available in applicant’s submitted documents. |

| Human judgment needed   | Medium — AI can verify income but loan officer must approve the final recommendation. |

| Integration possibility | Medium — Can integrate with loan management systems but requires data import from external sources. |

| Estimated time saving   | \~50% — Reduces manual review time from 30 minutes to 15 minutes per application. |



\*\*Human-in-the-loop role\*\*: Loan officer verifies AI’s income recommendation before making final approval.



\---



### **## ⚠️ \*\*Risks and Limitations\*\***



| Risk                                    | Level | Mitigation                                                 |

|-----------------------------------------|-------|------------------------------------------------------------|

| Data inconsistency (e.g., missing or incorrect income data) | High  | Ensure income data is complete and validated before processing. |

| AI might miss out on some contextual factors (e.g., irregular income sources) | Medium | Use supplementary data to verify applicant’s full financial situation. |

| Privacy concerns when handling sensitive financial documents | High  | Ensure compliance with data protection regulations (e.g., GDPR). |



\*\*Overall risk rating\*\*: Medium — The process is reliable but needs careful data handling and validation.



\---



### **## 🔄 \*\*Version History\*\***



\### **\*\*v1.0 — Initial Draft\*\***

\*\*Date\*\*: 2026-03-19  

\*\*Prompt\*\*: "Verify the income of the applicant by comparing the submitted financial documents with the income thresholds."  

\*\*Output\*\*: AI suggested loan approval based on income but lacked deeper validation for different income sources.  

\*\*Lesson learned\*\*: The initial version didn’t fully account for applicants with irregular income streams. 



\---



**### \*\*v1.1 — Improved Version\*\***

\*\*Date\*\*: 2026-03-23  

\*\*Change\*\*: Added context for varying income types (e.g., freelance, contract work).  

\*\*Output\*\*: AI now accounts for different employment types and sources of income.  

\*\*Lesson learned\*\*: Including more details about employment type improves accuracy in recommendations.



\---



**### \*\*v1.2 — Final Refinements ✅ Current\***\*

\*\*Date\*\*: 2026-04-01  

\*\*Change\*\*: Added a specific income threshold based on employment type to enhance decision-making.  

\*\*Output\*\*: Final output is more consistent, with clearer guidelines on income verification.  

\*\*Observed effect\*\*: Improved consistency and reduced manual follow-up required.  

\*\*Lesson learned\*\*: Defining a clear income threshold based on job type makes the process more reliable.



\---



**## 🔗 \*\*Related Prompts\*\***



\- \*\*Previous in chain\*\*: \[Link to previous prompt if chained]

\- \*\*Next in chain\*\*: \[Link to next prompt if chained]

\- \*\*Parent section\*\*: \[Link to section README]



\---



**### \*\*How to Use This Prompt:\*\***

1\. Replace the placeholders (`\[INCOME]`, `\[EMPLOYMENT\_TYPE]`, `\[INCOME\_THRESHOLD]`) with the applicant’s actual data before running the prompt in your AI system.

2\. Review the AI’s recommendation, and proceed with loan approval or rejection based on the income verification.



\---


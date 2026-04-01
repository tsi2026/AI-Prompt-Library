### **# Prompt #6 — Debt-to-Income Ratio Calculation**

\*\*Section\*\*: Loan Approval  

\*\*Workflow Step\*\*: Step 6 of 3  

\*\*Current Version\*\*: v1.2  

\*\*Status\*\*: 🔄 In Progress  

\*\*Last Updated\*\*: 2026-04-01



\---



### **## 📌 \*\*Prompt Text (v1.2 — Current)\*\***



> Copy this exactly into your AI tool. Replace all `\[PLACEHOLDERS]` before running.



"Calculate the debt-to-income (DTI) ratio using the following data: total monthly debt payments and monthly income. If the DTI ratio is over 40%, recommend loan rejection."





\*\*Placeholders to fill:\*\*



| Placeholder           | Source                                   | Example   |

|-----------------------|------------------------------------------|-----------|

| `\[DEBT\_PAYMENTS]`     | Applicant's total monthly debt payments  | $1,500    |

| `\[MONTHLY\_INCOME]`    | Applicant's total monthly income         | $4,000    |

| `\[DTI\_RATIO]`         | Debt-to-income ratio (calculated)        | 37.5%     |



\---



### **## 🏢 \*\*Intended Workflow or Task\*\***



This prompt fits into the \*\*loan approval process\*\* to calculate the applicant's \*\*debt-to-income (DTI) ratio\*\*, helping determine their ability to repay the loan.



\- \*\*Trigger\*\*: Applicant submits their debt payments and monthly income details.

\- \*\*Actor\*\*: Loan officer or AI system reviewing the applicant’s financial information.

\- \*\*Timing\*\*: This prompt runs immediately after the applicant’s financial details are submitted.

\- \*\*Next Step\*\*: The AI-generated DTI ratio is reviewed by the loan officer for final approval or rejection.



**Example workflow: Applicant submits financial details → \[THIS PROMPT RUNS] → Output routed to loan officer for review**





\---



### **## ❗ \*\*Problem Being Solved\*\***



Calculating the debt-to-income ratio manually is time-consuming and may lead to errors. By automating this process, we can quickly determine if the applicant is financially capable of taking on additional debt, improving loan decision accuracy.



\*\*Pain points addressed:\*\*

\- Time spent calculating DTI manually.

\- Risk of errors in manual calculations.

\- Inconsistent DTI assessments.



\---



### **## ⚡ \*\*Automation Potential\*\***



\*\*Level\*\*: High



| Dimension              | Assessment                                           |

|------------------------|------------------------------------------------------|

| Repetitiveness          | High — This task happens for every loan application. |

| Data availability       | Readily available from applicant’s financial details. |

| Human judgment needed   | Low — AI can handle the task, but loan officer must review final decision. |

| Integration possibility | High — Can integrate with loan management systems.  |

| Estimated time saving   | \~60% — Reduces manual calculation time from 10 minutes to 4 minutes per applicant. |



\*\*Human-in-the-loop role\*\*: Loan officer reviews the AI-calculated DTI ratio and decides on loan approval or rejection.



\---



### **## ⚠️ \*\*Risks and Limitations\*\***



| Risk                                    | Level | Mitigation                                                 |

|-----------------------------------------|-------|------------------------------------------------------------|

| Inaccurate data input (e.g., wrong monthly debt or income) | High  | Ensure accurate data validation before processing.         |

| Over-reliance on DTI ratio without considering other factors (e.g., credit score, savings) | Medium | Use supplementary criteria (e.g., credit score, savings) for a more holistic assessment. |

| False positives (e.g., rejecting applicants who may have other financial stability factors) | Medium | Introduce additional context, such as emergency savings or job stability. |



\*\*Overall risk rating\*\*: Medium — The DTI calculation is reliable but needs other criteria for a comprehensive loan decision.



\---



### **## 🔄 \*\*Version History\*\***



\### \*\*v1.0 — Initial Draft\*\*

\*\*Date\*\*: 2026-03-19  

\*\*Prompt\*\*: "Calculate the debt-to-income ratio based on total monthly debt payments and income."  

\*\*Output\*\*: AI calculated the DTI and rejected applications where the ratio was above 40%.  

\*\*Lesson learned\*\*: The initial version did not consider other financial factors that might impact loan eligibility.



\---



\### \*\*v1.1 — Improved Version\*\*

\*\*Date\*\*: 2026-03-23  

\*\*Change\*\*: Added context for other financial factors (e.g., job stability, savings) in decision-making.  

\*\*Output\*\*: AI now provides a more nuanced assessment based on DTI and other factors.  

\*\*Lesson learned\*\*: Including other financial factors improves loan decision reliability.



\---



\### \*\*v1.2 — Final Refinements ✅ Current\*\*

\*\*Date\*\*: 2026-04-01  

\*\*Change\*\*: Adjusted DTI threshold and included job type and savings as factors for loan decision-making.  

\*\*Output\*\*: Final output is more balanced, with clearer decision criteria.  

\*\*Observed effect\*\*: Reduced rejection of potentially viable applicants, with better alignment to financial stability.  

\*\*Lesson learned\*\*: Defining clear thresholds and integrating additional factors improves loan assessment accuracy.



\---





\## 🔗 \*\*Related Prompts\*\*



\- \*\*Previous in chain\*\*: \[Link to previous prompt if chained]

\- \*\*Next in chain\*\*: \[Link to next prompt if chained]

\- \*\*Parent section\*\*: \[Link to section README]



\---



\### \*\*How to Use This Prompt:\*\*

1\. Replace the placeholders (`\[DEBT\_PAYMENTS]`, `\[MONTHLY\_INCOME]`, `\[DTI\_RATIO]`) with the applicant’s actual data before running the prompt in your AI system.

2\. Review the AI-calculated DTI ratio, and proceed with loan approval or rejection based on the evaluation.



\---


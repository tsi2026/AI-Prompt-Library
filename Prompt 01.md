### Prompt01 — Credit Score Evaluation



**Section:** Loan Approval

**Workflow Step:** Step 1 of 3

**Current Version:** v1.0

**Status:** 🔄 In Progress

**Last Updated:** 01-04-2026



**📌 Prompt Text (v1.0 — Current)**

---

You are a loan officer. Evaluate the creditworthiness of a loan applicant based on the following input data: credit score, income, and debt-to-income ratio. If the credit score is above 650 and debt-to-income ratio is below 40%, recommend loan approval.



Placeholders to fill 



Placeholder               Source                      Example

\[Credit Score]      Applicant's Credit Score           700

\[Income]	      Applicant's Income              $50,000

\[Debt to Income]    Applicant's Debt to income ratio    30%



### **🏢 Intended Workflow or Task**



This prompt is used in the loan approval process to evaluate the applicant's creditworthiness based on key financial indicators.



**Trigger:** Loan application submitted by the applicant.

**Actor:** Loan officer or AI system reviewing the application.

**Timing:** This prompt runs immediately after the applicant submits their financial data.

**Next Step:** AI recommendation sent to loan officer for final review or approval.



**Example workflow: Customer submits loan application → \[THIS PROMPT RUNS] → Output routed to loan officer for review**



### **❗ Problem Being Solved**



The manual evaluation of creditworthiness is time-consuming, prone to human error, and inconsistent across loan officers. By automating this process, we save time, reduce errors, and speed up the approval process.



**Pain points addressed:**



Time spent manually reviewing credit scores.

Errors due to inconsistent data input.

Delays in loan approval process.



### 

### **⚡ Automation Potential**



**\*\*Level\*\*: High**



**| Dimension              | Assessment                                           |**

**|------------------------|------------------------------------------------------|**

**| Repetitiveness          | High — This task happens for every loan application. |**

**| Data availability       | Readily available in CRM system or applicant form.  |**

**| Human judgment needed   | Low — AI can handle the task, but human review is required. |**

**| Integration possibility | High — Can integrate with loan management systems.  |**

**| Estimated time saving   | \~60% — Reduces manual review from 30 minutes to 12 minutes. |**



**\*\*Human-in-the-loop role\*\*: Loan officer verifies the AI recommendation before sending final approval.**





### **⚠️ Risks and Limitations**



| Risk                                    | Level | Mitigation                                                 |

|-----------------------------------------|-------|------------------------------------------------------------|

| Inaccurate data input (e.g., malformed credit score or income data) | High  | Ensure data is validated before processing.                |

| Bias in credit score interpretation     | Medium | Regularly update AI model to ensure fair evaluation.       |

| Lack of context (e.g., job stability or medical expenses) | Medium | Use additional data points like employment history for better decision-making. |



**\*\*Overall risk rating\*\*: Medium — The prompt requires accurate input data, but once validated, it functions well.**





### **🔄 Version History**



**### v1.0 — Initial Draft**

\*\*Date\*\*: 2026-03-19

\*\*Prompt\*\*: "Evaluate the creditworthiness of a loan applicant based on their credit score and income."  

\*\*Output\*\*: AI suggested loan approval, but missed additional factors like debt-to-income ratio.  

\*\*Lesson learned\*\*: The initial version lacked a more comprehensive view of financial health.



\---



**### v1.1 — Improved Version**

\*\*Date\*\*: 2026-03-23

\*\*Change\*\*: Added debt-to-income ratio to the prompt for more accuracy in assessing affordability.  

\*\*Output\*\*: Improved decision accuracy.  

\*\*Lesson learned\*\*: Including more financial criteria improved loan decision reliability.



\---



**### v1.2 — Final Refinements ✅ Current**

\*\*Date\*\*: 2026-04-01

\*\*Change\*\*: Adjusted the tone and added a clearer set of criteria.  

\*\*Output\*\*: Final output is more consistent and better aligns with the loan approval process.  

\*\*Observed effect\*\*: Measurable improvement in decision consistency, reducing manual follow-ups.  

\*\*Lesson learned\*\*: Clear constraints and more detailed financial factors lead to better automation outcomes.



\---

### 

### **## 🔗 Related Prompts**



\- \*\*Previous in chain\*\*: \[Link to previous prompt if chained]

\- \*\*Next in chain\*\*: \[Link to next prompt if chained]

\- \*\*Parent section\*\*: \[Link to section README]



\---



**### How to Use This Prompt:**

1\. Replace the placeholders (`\[CREDIT\_SCORE]`, `\[INCOME]`, `\[DEBT\_TO\_INCOME]`) with the applicant’s actual data before running the prompt in your AI system.

2\. Review the recommendation from AI, and make final approval or rejection based on the provided data.












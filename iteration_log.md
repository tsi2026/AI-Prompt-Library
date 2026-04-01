# Iteration Logs for AI Prompt Library

## Iteration Log for Prompt #1 — Credit Score Evaluation

### v1.0 — Initial Version
- **Change Made**: Initial draft of the prompt.
- **Observed Effect**: The output was too generic; no specific conditions for approval.
- **Lesson Learned**: Needed role + context constraints to make the evaluation more precise.

### v1.1 — Improved Version
- **Change Made**: Added role and context constraints for better clarity.
- **Observed Effect**: Better tone; output still lacked an explicit format.
- **Lesson Learned**: Adding a clear format structure is necessary for consistent output.

### v1.2 — Final Refinements
- **Change Made**: Explicit output structure added and conditions clearly defined.
- **Observed Effect**: Clearer, more accurate outputs with consistent formatting.
- **Lesson Learned**: Adding explicit constraints and output format results in reliable and clear outputs.

---

## Iteration Log for Prompt #2 — Income Verification

### v1.0 — Initial Version
- **Change Made**: Simple prompt asking to verify applicant income based on documents.
- **Observed Effect**: Basic calculation; didn’t account for varied income types like freelance or self-employed.
- **Lesson Learned**: Need to add context for different income sources for a comprehensive verification.

### v1.1 — Improved Version
- **Change Made**: Added additional context like freelance income and self-employed applicants.
- **Observed Effect**: AI now considers different employment types, making the check more accurate.
- **Lesson Learned**: Contextual data like income type improves the verification process.

### v1.2 — Final Refinements
- **Change Made**: Added clear income thresholds and validation to prevent false positives.
- **Observed Effect**: More accurate verification, with better handling of edge cases like irregular income.
- **Lesson Learned**: Clear income thresholds and supplementary data improve overall verification accuracy.

---

## Iteration Log for Prompt #3 — Loan Type Recommendation

### v1.0 — Initial Version
- **Change Made**: Loan type recommended based only on credit score.
- **Observed Effect**: Loan recommendations lacked nuance and context.
- **Lesson Learned**: Relying solely on credit score misses important financial data points like income.

### v1.1 — Improved Version
- **Change Made**: Added income and debt-to-income ratio as additional factors.
- **Observed Effect**: The AI recommendation was more nuanced, considering more than just credit score.
- **Lesson Learned**: More factors make loan type recommendations more accurate.

### v1.2 — Final Refinements
- **Change Made**: Adjusted the thresholds for loan type recommendations based on broader financial data.
- **Observed Effect**: Improved loan matching to the applicant's financial situation.
- **Lesson Learned**: A more holistic view of the applicant’s finances leads to better loan recommendations.

---

## Iteration Log for Prompt #4 — Risk Assessment Based on Past Defaults

### v1.0 — Initial Version
- **Change Made**: Focused on defaults alone to assess risk.
- **Observed Effect**: The output was too rigid and missed applicants who may have improved their financial situation.
- **Lesson Learned**: Need to include additional financial context like current income and savings.

### v1.1 — Improved Version
- **Change Made**: Added payment history and recent financial behavior to assess risk more accurately.
- **Observed Effect**: The AI now considers more than just defaults, allowing for a better risk assessment.
- **Lesson Learned**: A broader set of financial factors results in a more accurate risk score.

### v1.2 — Final Refinements
- **Change Made**: Added job stability and savings as further risk evaluation factors.
- **Observed Effect**: Better identification of low-risk applicants with a stable financial background.
- **Lesson Learned**: Including job stability and savings improves the reliability of risk assessments.

---

## Iteration Log for Prompt #5 — Fraud Detection in Loan Applications

### v1.0 — Initial Version
- **Change Made**: Basic fraud detection based on mismatched personal details and suspicious patterns.
- **Observed Effect**: The AI flagged too many applications as fraudulent, resulting in false positives.
- **Lesson Learned**: Need to refine fraud detection rules to prevent over-flagging.

### v1.1 — Improved Version
- **Change Made**: Added more refined detection rules, including income thresholds and document checks.
- **Observed Effect**: Fewer false positives; better fraud detection accuracy.
- **Lesson Learned**: More specific detection rules help improve the accuracy of fraud detection.

### v1.2 — Final Refinements
- **Change Made**: Adjusted for manual overrides and added checks for additional verification before flagging.
- **Observed Effect**: Reduced false positives while ensuring that legitimate fraud cases are flagged.
- **Lesson Learned**: Balancing automated detection with manual review provides the best fraud detection results.

---

## Iteration Log for Prompt #6 — Debt-to-Income Ratio Calculation

### v1.0 — Initial Version
- **Change Made**: Prompt simply calculated DTI ratio based on income and debt payments.
- **Observed Effect**: The calculation worked, but didn’t account for varying factors like loans with different terms.
- **Lesson Learned**: DTI should include more flexibility in loan term evaluation for better decisions.

### v1.1 — Improved Version
- **Change Made**: Added loan terms and income variations for more accurate DTI calculations.
- **Observed Effect**: The AI now provides a more accurate financial evaluation.
- **Lesson Learned**: Including loan terms and income factors makes DTI more reliable for loan decisions.

### v1.2 — Final Refinements
- **Change Made**: Adjusted DTI thresholds for different types of loans (e.g., personal vs. mortgage).
- **Observed Effect**: More tailored DTI evaluations based on loan type and applicant’s financial history.
- **Lesson Learned**: Loan type consideration and financial history help create better loan approval decisions.

---

## Iteration Log for Prompt #7 — Loan Approval Notification Draft

### v1.0 — Initial Version
- **Change Made**: Basic loan approval email format with no personalization.
- **Observed Effect**: The email lacked a personal touch, making it feel impersonal.
- **Lesson Learned**: Personalizing the email improves applicant satisfaction.

### v1.1 — Improved Version
- **Change Made**: Added applicant’s name and loan details.
- **Observed Effect**: The email is now more personalized and professional.
- **Lesson Learned**: Personalization increases engagement and satisfaction with the approval message.

### v1.2 — Final Refinements
- **Change Made**: Included clear repayment details and payment schedule.
- **Observed Effect**: Better clarity and professionalism in communication with the applicant.
- **Lesson Learned**: Clear, detailed terms increase understanding and trust in the approval process.

---

## Iteration Log for Prompt #8 — Loan Rejection Letter Draft

### v1.0 — Initial Version
- **Change Made**: Basic rejection letter with no empathy.
- **Observed Effect**: The tone of the rejection came across as impersonal and harsh.
- **Lesson Learned**: The tone in rejection letters needs to be empathetic and professional.

### v1.1 — Improved Version
- **Change Made**: Added empathetic language and encouragement for future applications.
- **Observed Effect**: The rejection letter now feels more professional and respectful.
- **Lesson Learned**: Empathetic communication softens the rejection and maintains applicant relationships.

### v1.2 — Final Refinements
- **Change Made**: Included specific feedback for rejection reasons and suggested ways for improvement.
- **Observed Effect**: Rejection reasons are clearly communicated, and applicants feel more informed and encouraged.
- **Lesson Learned**: Providing feedback along with the rejection helps applicants improve and reapply.

---

## Iteration Log for Prompt #9 — Loan Terms Calculation

### v1.0 — Initial Version
- **Change Made**: Loan terms based solely on credit score.
- **Observed Effect**: The loan terms were inconsistent and not fully reflective of the applicant’s complete financial profile.
- **Lesson Learned**: Loan terms need to consider additional factors like income and loan amount.

### v1.1 — Improved Version
- **Change Made**: Added income and loan amount as additional factors for calculating loan terms.
- **Observed Effect**: More balanced loan terms tailored to the applicant’s financial capacity.
- **Lesson Learned**: Adding more financial details results in better-aligned loan terms.

### v1.2 — Final Refinements
- **Change Made**: Adjusted thresholds for loan amounts and interest rates based on applicant’s full financial picture.
- **Observed Effect**: More accurate loan offers, better reflecting the applicant’s ability to repay.
- **Lesson Learned**: A more comprehensive approach to calculating loan terms increases approval accuracy.

---

## Iteration Log for Prompt #10 — Reporting for Compliance

### v1.0 — Initial Version
- **Change Made**: Generated a basic report with loan application status.
- **Observed Effect**: The report was too basic and lacked important compliance data.
- **Lesson Learned**: Compliance reports need to be comprehensive, with full details on loan amounts, statuses, and reasons for rejection.

### v1.1 — Improved Version
- **Change Made**: Added more detailed fields for loan rejection reasons and applicant names.
- **Observed Effect**: Reports became more complete and aligned with regulatory requirements.
- **Lesson Learned**: Including all necessary data improves the quality and usability of compliance reports.

### v1.2 — Final Refinements
- **Change Made**: Enhanced formatting and added compliance checks for better readability.
- **Observed Effect**: More user-friendly and regulatory-compliant reports.
- **Lesson Learned**: Structuring the report properly ensures that it meets compliance and is easy to interpret.

---

Added iteration logs for all prompts

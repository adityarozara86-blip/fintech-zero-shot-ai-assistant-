Lab 1 : zero-shot prompting 



objectives 

Show that you can write precise zero-shot prompts for finance tasks, check the output yourself, and improve the prompt with evidence.

Show that you can write precise zero-shot prompts for finance tasks, check the output yourself, and improve the prompt with evidence.





Tasks 

1..Prompt any AI tool: "Explain EMI to a first-year BBA FinTech student in 50 words." Record the output.



\- \[x]  —EMI (Equated Monthly Instalment) is a fixed amount paid every month to repay a loan. It includes both the principal amount borrowed and the interest charged by the lender. EMI makes loan repayment easier by dividing the total amount into smaller, regular monthly payments over a specific period.



2..Write an improved prompt for a ₹2,50,000 personal loan at 14% annual interest for 24 months. Ask for the formula, monthly EMI, total repayment and total interest in a table.





\- \[x] —Act as a financial expert and explain the EMI calculation for a personal loan of ₹2,50,000 at an annual interest rate of 14% for a repayment period of 24 months.

\* Include the following:

\* Explain the EMI formula.

\* Show the step-by-step calculation.

\* Calculate the monthly EMI.

\* Calculate the total repayment amount over 24 months.

\* Calculate the total interest payable.

\* Present all results in a clear table with the following columns: Particulars, Formula/Calculation, and Amount (₹).

\* Use simple language suitable for a first-year BBA FinTech student. Round off amounts to two decimal places.



3..Calculate the EMI yourself in a spreadsheet using the formula EMI = P × r × (1 + r)^n ÷ \[(1 + r)^n − 1]. State whether the AI was correct, and by how much it differed if not.











\- \[x] —EMI Calculation – Personal Loan

\* Given details:

Particulars	Value

Loan amount (P)	₹2,50,000

Annual interest rate	14%

Monthly interest rate (r)	14% ÷ 12 = 1.1667%

Loan tenure (n)	24 months

1\. EMI Formula

\* \\\[ EMI=\\frac{P\\times r\\times(1+r)^n}{(1+r)^n-1} \\]

\* Substituting the values:

\* \\\[ EMI=\\frac{250000\\times0.011667\\times(1.011667)^{24}}{(1.011667)^{24}-1} \\]

\* 2. Final Results

Particulars	Amount

Monthly EMI	₹12,003.22

Total repayment	₹2,88,077.30

Total interest	₹38,077.30

3\. Was the AI correct?

\* The earlier AI response explained the meaning of EMI correctly, but it did not calculate a numerical EMI.

\* Therefore, there is no numerical difference to compare.

\* Independently calculated EMI: ₹12,003.22



\* Difference from earlier AI calculation: Not applicable.



\* Independent calculation completed

\* 4. Spreadsheet

\* Download the EMI Calculation Spreadsheet

\* Conclusion: For a personal loan of ₹2,50,000 at 14% annual interest over 24 months, the monthly EMI is ₹12,003.22, and the total interest payable is ₹38,077.30.



Task 2 :Task 2: Complaint classification



Act as a FinTech complaint classification assistant.



Classify the following customer complaint into exactly one category: Payments, Loans, or KYC/Account. If the category is unclear, label it Needs review.



Customer complaint: "EMI deducted twice."



Return a table with Complaint, Category, Reason, and Recommended Action. Do not provide any classification examples.



compliment	Category	Reason	Recommended Action

EMI deducted twice.	Loans	The complaint relates to a duplicate EMI deduction from a loan account.	Verify the loan repayment statement, check both transactions, and initiate a refund for the duplicate deduction if confirmed.



&#x20;



Task 3: Summarise without inventing



Give the AI this fictional passage and ask for a 3-bullet factual summary plus a list of what cannot be concluded



"PaySetu, a fictional payments start-up, processed 4.2 lakh transactions in September and 5.1 lakh in October. Average transaction value fell from ₹640 to ₹590. Server downtime increased in October. No data is available on revenue or costs."

Calculate the total transaction value for both months yourself and mark any statement in the AI output that goes beyond the passage.



PaySetu – Transaction Value Calculation

Formula:

Total Transaction Value = Number of Transactions × Average Transaction Value

1\. Calculations

September:

= 4,20,000 × ₹640

= ₹26,88,00,000 (₹26.88 crore)

October:

= 5,10,000 × ₹590

= ₹30,09,00,000 (₹30.09 crore)

2\. Results Table

Particulars	September	October

Number of transactions	4.2 lakh	5.1 lakh

Average transaction value	₹640	₹590

Total transaction value	₹26.88 crore	₹30.09 crore

Server downtime	Not specified	Increased

3\. Comparison

\* Transaction volume increased by approximately 21.43%.



\* Average transaction value decreased by approximately 7.81%.



\* Total transaction value increased by ₹3.21 crore (11.94%).



4\. Statements that go beyond the passage

The following claims would be unsupported if included in an AI-generated analysis:

AI statement	Assessment

PaySetu's revenue increased.	Unsupported

Revenue data is unavailable.

PaySetu's profits improved.	Unsupported

Cost and profit data are unavailable.

Server downtime caused transaction value to decrease.	Unsupported

No causal relationship is established.

October transaction volume increased.	Supported

Increased from 4.2 lakh to 5.1 lakh.

October total transaction value increased.	Supported

Increased from ₹26.88 crore to ₹30.09 crore.

Conclusion: PaySetu's total transaction value increased by 11.94% in October despite a decline in average transaction value. However, revenue, profitability, costs and the financial impact of server downtime cannot be determined from the given information.



task 4: Translate and write

Payment Failed

Dear Customer,

Your payment of ₹2,500 could not be completed due to a technical issue.

Transaction Status: Failed

Amount: ₹2,500

Reason: Technical error

If the amount has been deducted from your account, please contact customer support for assistance.

Please check your transaction history before retrying the payment.

PaySetu Support Team





1\.	Translate a failed-payment notification into Hindi without adding any promise or date that is not in the original. Back-translate it into English to check.

1\. Hindi translation

Writing

भुगतान विफल

प्रिय ग्राहक,

तकनीकी समस्या के कारण आपका ₹2,500 का भुगतान पूरा नहीं हो सका।

लेन-देन की स्थिति: विफल

राशि: ₹2,500

कारण: तकनीकी त्रुटि

यदि आपके खाते से राशि कट गई है, तो सहायता के लिए कृपया ग्राहक सहायता टीम से संपर्क करें।

भुगतान दोबारा करने से पहले कृपया अपने लेन-देन का इतिहास जाँच लें।

PaySetu सहायता टीम

2\. English back-translation

Writing

Payment Failed

Dear Customer,

Your payment of ₹2,500 could not be completed due to a technical problem.

Transaction Status: Failed

Amount: ₹2,500

Reason: Technical error

If the amount has been deducted from your account, please contact the customer support team for assistance.

Please check your transaction history before making the payment again.

PaySetu Support Team

3\. Translation accuracy check

Checkpoint	Result

Payment amount ₹2,500	Accurate

Failed transaction status	Accurate

Technical error reason	Accurate

Contact customer support if amount was deducted	Accurate

Check transaction history before retrying	Accurate

Additional refund promise or date	None added

Conclusion: The Hindi translation preserves the original notification's meaning. The back-translation confirms that no additional refund guarantee, resolution date, or payment-processing promise has been introduced.

2\.	Draft a 100-word email from an operations executive to a partner bank about a delayed settlement, using \[placeholders] for all IDs, amounts and dates.

Dear Partner Bank Team,

We are writing to bring to your attention a delay in the settlement of transactions associated with \[Settlement ID] for the amount of \[Amount]. The expected settlement date was \[Date], but the funds have not yet been credited to our account.

We kindly request you to investigate this delay and share the current settlement status along with the expected resolution date. Please treat this matter as a priority to avoid further operational disruptions.

Thank you for your cooperation and support.

Regards,
Operations Executive
\[Company Name]


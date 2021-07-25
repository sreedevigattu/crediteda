Risk analytics in banking and financial services

Data is used to minimise the risk of losing money while lending to customers.
the applicants capable of repaying the loan are not rejected.
identify patterns which indicate if a client has difficulty paying their installments
the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. 


Data about each applicant
- The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,    
- All other cases: All other cases when the payment is paid on time.

Decisions that could be taken by the client/company):
- Approved: The Company has approved loan Application
- Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.
- Refused: The company had rejected the loan (because the client does not meet their requirements etc.).
- Unused offer:  Loan has been cancelled by the client but on different stages of the process.


1. 'application_data.csv'  contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties.
2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.

# Bank Credit EDA – A Case Study

This Exploratory Data Analysis case study has been done as a part of my assignment in Post Graduate Program in Data Science and AI from IIIT-B.

## Introduction

When a bank reviews a loan application, it must determine whether to approve the loan based on the applicant's profile. There are two main risks involved in this decision:

1. If the applicant is expected to repay the loan, rejecting the application could mean losing out on potential business for the bank.

2. If the applicant is unlikely to repay the loan and is expected to default, approving the loan might result in financial losses for the bank.

## Key Factors of Data

The data given here contains the information about the loan application at the time of applying for the loan. It contains two scenarios:
1. The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,
2. All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/bank):

a. Approved: The bank has approved loan Application

b. Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client, he received worse pricing which he did not want.

c. Refused: The bank had rejected the loan (because the client does not meet their requirements etc.).

d. Unused offer:  Loan has been cancelled by the client but at different stages of the process.

## Objective

1. This case study seeks to pinpoint patterns that suggest a client may struggle with paying their installments.

2. These insights can inform decisions such as denying the loan, adjusting the loan amount, or charging higher interest rates for riskier applicants.

3. The bank aims to uncover the key factors behind loan defaults—those variables that most strongly predict default. By understanding these factors, the bank can better manage its portfolio and assess risk.





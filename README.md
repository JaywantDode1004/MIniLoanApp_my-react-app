#Mini Loan Application

Features
1. Loan Creation by Customers
Customers can initiate a loan request through the system by specifying the loan amount and term. Upon creating a loan request, the system automatically generates a schedule for repayments.

Example: A customer requests a loan of $10,000 with a 3-month term on 7th February 2022. The system generates three scheduled repayments:
14th February 2023: $3,333.33
21st February 2023: $3,333.33
28th February 2023: $3,333.34
At this stage, both the loan and its scheduled repayments are marked as PENDING.
2. Loan Approval by Admins
Loan administrators have the capability to review PENDING loans and approve them. Once approved, the loan status transitions to APPROVED, signaling that the borrower can start making repayments.

3. Viewing Loans by Customers
Customers have the ability to view details of the loans tied to them. A security policy ensures that customers can only access their own loan information, thereby protecting user data and ensuring privacy.

4. Repayments by Customers
Borrowers can submit repayments for their loans through the system. A repayment must be equal to or greater than the scheduled repayment amount to be accepted. Upon submission:

The corresponding scheduled repayment status changes to PAID.
If all repayments for a loan are marked as PAID, the loan's overall status updates to PAID, indicating the loan has been fully settled.

# Home Page
![image](https://github.com/JaywantDode1004/MIniLoanApp_my-react-app/assets/136264417/f70e64d4-f5f1-44ef-8358-79c80bdc2ddf)

# Customer Creating Loan
![image](https://github.com/JaywantDode1004/MIniLoanApp_my-react-app/assets/136264417/fa0aaaf3-ae54-41f8-8214-37876bfaf43e)

# Customer can check their loan status 
![image](https://github.com/JaywantDode1004/MIniLoanApp_my-react-app/assets/136264417/8611c23d-9074-4e83-a7ee-e89b34a24a3c)

# Customer can repay their loan by their loanid
![image](https://github.com/JaywantDode1004/MIniLoanApp_my-react-app/assets/136264417/5044e482-bc0f-4513-bca1-431d7b604b1c)

#Thankyou for repayment
![image](https://github.com/JaywantDode1004/MIniLoanApp_my-react-app/assets/136264417/328c344a-a7ec-4d0b-b134-9d389b982f62)





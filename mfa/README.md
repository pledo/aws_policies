# AWS IAM Policy: Force_MFA



### Actions:

- Allow All Users To List Accounts and the users
- AllowIndividualUserToSeeTheirAccountInformation
- AllowIndividualUserToListTheirMFA
- AllowIndividualUserToManageThierMFA

**Condition:**
Do Not Allow Any thing Other Than Above Unless MFAd


**Important note:**
The existed users should enable the MFA and after that log out and log into the AWS account to perform their actions.


**Source:** 
- https://aws.amazon.com/blogs/security/how-to-delegate-management-of-multi-factor-authentication-to-aws-iam-users/

- https://s3.amazonaws.com/awsiammedia/public/sample/DelegateManagementofMFA/DelegateManagementofMFA_policydocument_060115.txt


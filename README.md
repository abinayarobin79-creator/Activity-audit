# Activity-audit
NAME : Abinaya R

REG.NO : 212225230004

DATE : 28/08/2026

EXPERIMENT 4

ASSET-ORIENTED RISK ASSESSMENT OF STORAGE ASSETS IN AWS AND AZURE

Objective

To identify storage assets in AWS S3 and Microsoft Azure Blob Storage, identify possible vulnerabilities and threats, and assess their likelihood, impact, and risk level.

1. Software / Cloud Services Required

• AWS Account

• Microsoft Azure Account

• Web Browser

• Internet Connection

Cloud Services Used

Cloud Platform Storage Service

AWS Amazon S3

Microsoft Azure Azure Blob Storage

PART A — AWS S3 STORAGE ASSESSMENT

Step 1: Login to AWS

Open the AWS Management Console.

Sign in using your AWS account.

Search for S3.

Select Amazon S3.

Step 2: Select the S3 Bucket

Click Buckets.

Select the S3 bucket created in the previous experiment.

Record:

o Bucket name

o AWS Region

o Number/type of objects

<img width="1920" height="1080" alt="Screenshot 2026-08-28 135723" src="https://github.com/user-attachments/assets/7e6541c0-6b68-4641-9956-99169ae11764" />


Screenshot 2026-08-21 133706
Step 3: Check Block Public Access

Open the S3 bucket.

Select Permissions.

Locate Block public access (bucket settings).

Check Block all public access.

Record:

• ON → Secure configuration

• OFF → Potential public-access risk

<img width="1920" height="1080" alt="Screenshot 2026-08-28 135806" src="https://github.com/user-attachments/assets/98dc4f2f-5ab7-41df-a6c6-4ee6b1b179ef" />


Step 4: Check Bucket Versioning

Select the Properties tab.

Locate Bucket Versioning.

Record whether it is:

o Enabled

o Disabled

Security purpose

Versioning helps recover previous versions of objects after accidental deletion or modification.

<img width="1920" height="1080" alt="Screenshot 2026-08-28 135835" src="https://github.com/user-attachments/assets/510bbb12-7948-4ab8-9d5b-fc7832f20630" />



Step 5: Check Default Encryption

Stay in the Properties tab.

Locate Default encryption.

Record the encryption type.

Possible configurations include:

• SSE-S3

• SSE-KMS

• DSSE-KMS

Security purpose

Encryption protects stored data from unauthorized disclosure.

<img width="1920" height="1080" alt="Screenshot 2026-08-28 135917" src="https://github.com/user-attachments/assets/d5160b9a-804a-4205-8c58-c8d9cd06c8e0" />



Step 6: Check Bucket Policy

Select Permissions.

Locate Bucket policy.

Check whether a bucket policy exists.

Record:

• Policy exists

• No policy

Note

A missing bucket policy is not automatically a vulnerability. Access may be controlled through IAM and other AWS security mechanisms.

<img width="1920" height="1080" alt="Screenshot 2026-08-28 135917" src="https://github.com/user-attachments/assets/4f4a0168-d341-4616-b436-c50b32fca79d" />


Step 7: Check Object Ownership and ACL

In Permissions, locate Object Ownership.
Record the current configuration.
A common secure configuration is:

Bucket owner enforced

This means:

• ACLs are disabled.

• Objects are owned by the bucket owner.

• Access is controlled using policies.

<img width="1920" height="1080" alt="Screenshot 2026-08-28 135917" src="https://github.com/user-attachments/assets/608befd7-5500-4d10-b471-60fc42407c4c" />


Step 8: Check Server Access Logging

Go to Properties.

Locate Server access logging.

Record whether it is:

o Enabled

o Disabled

Security purpose

Logging helps investigate suspicious or unauthorized access to the bucket.

<img width="1920" height="1080" alt="Screenshot 2026-08-28 135917" src="https://github.com/user-attachments/assets/4e8a69a9-f817-42cf-b4b4-fca25906a8eb" />


PART B — AWS RISK ASSESSMENT

After checking the S3 configuration, identify possible vulnerabilities and threats.

Risk Formula

Risk Score = Likelihood × Impact

Use the following scale.

Likelihood

<img width="185" height="203" alt="Screenshot 2026-08-28 141732" src="https://github.com/user-attachments/assets/8d178e6e-8f89-49c8-a27b-55e6b2737a7d" />


Sample AWS Risk Assessment

<img width="812" height="258" alt="Screenshot 2026-08-28 141755" src="https://github.com/user-attachments/assets/ce1fc76f-12a6-43fe-ac6b-93c57813e317" />


<img width="792" height="305" alt="Screenshot 2026-08-28 141805" src="https://github.com/user-attachments/assets/2bfbfd67-aa5a-4d6e-8907-08ec0ce28646" />



RESULT

The storage assets in AWS S3 were identified and analyzed. Various security configurations, vulnerabilities, threats, likelihood, and impacts were evaluated. Risk scores were calculated using the Likelihood × Impact method, and appropriate security mitigation measures were recommended.

About
No description, website, or topics provided.
Resources
Readme
Activity
Stars
0 stars
Watchers
0 watching
Forks
0 forks
Report repository
Releases
No releases published
Packages
No packages published
Contributors
No contributors
Footer

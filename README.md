This repository contains various AWS IAM configurations to manage secure access control.

-It includes an IAM role for EC2 with S3 read-only access, allowing instances to retrieve data from S3.
-An IAM user was created with programmatic access restricted to read-only operations on S3.
-An IAM group was created to manage EC2 permissions efficiently.
-Multi-Factor Authentication (MFA) was enabled for IAM users to enhance security.
-A custom S3 read-only policy was implemented to enforce controlled access.

These configurations help in managing AWS resources securely while ensuring the principle of least privilege.

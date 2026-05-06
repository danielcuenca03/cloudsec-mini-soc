Session 1–2: AWS Security Foundation and Documentation
Completed: Secured the AWS root account with MFA and confirmed no root access keys. Created an admin IAM user (cse-admin) and enabled MFA. Created a standard IAM user (cse-dev) with no permissions as a least-privilege baseline. Configured a $10 monthly budget with alerts. Created a private S3 bucket for CloudTrail logs with Block Public Access enabled, default encryption (SSE-S3), and versioning enabled. Created a CloudTrail trail and verified logging is active. Documented baselines in GitHub and uploaded evidence screenshots.

Session 3A: IAM Least Privilege Build
Completed: Created an “app-data” S3 bucket and attached a least-privilege IAM policy to cse-dev to allow only scoped access to that bucket.

Next: Log in as cse-dev to test allowed and denied actions, capture evidence screenshots, and write the IAM test results (Session 4).

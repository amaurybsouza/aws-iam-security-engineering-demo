### AWS IAM best practices
To help secure your AWS resources, follow these best practices for IAM:

- Require human users to use federation with an identity provider to access AWS using temporary credentials.
- Require workloads to use temporary credentials with IAM roles to access AWS.
- Rotate access keys regularly for use cases that require long-term credentials.
- Require MFA.
- Safeguard your root user credentials and don't use them for everyday tasks.
- Apply least-privilege permissions.
- Regularly review and remove unused users, roles, permissions, policies, and credentials.

### Some things you can do...
- Get started with AWS managed policies and move toward least-privilege permissions.
- Use IAM Access Analyzer to generate least-privilege policies based on access activity.


